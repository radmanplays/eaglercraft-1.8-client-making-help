# Requirements

So you have decided to try and make a client for eaglercraft 1.8 and here you are. For this tutorial you will need:
- A decent enough computer running 64-bit Windows.
- A ZIP archive manager (WinRAR, 7-zip)
- ModCoderPack 1.8.8 (mcp918.zip) [https://modcoderpack.com/](https://modcoderpack.com/)
- FFMPEG [Download](https://www.gyan.dev/ffmpeg/builds/packages/ffmpeg-2023-01-04-git-4a80db5fc2-full_build.7z)
- Minecraft 1.8.8 jar [Download](https://mcversions.net/download/1.8.8)
- Java version 11 or newer
- Eclipse IDE

# Getting started

## a. Creating our workspace
1. Navigate to your desktop<br/>
2. Right-click and select new<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/211144896-7e317941-46d0-4e32-8737-59a28cf19263.png)<br/>
3. Click on ```Folder```.<br/>
4. Name it how you want.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/211144909-b97aec17-be21-44a3-8e49-181be8a26905.png)<br/>

## b. Installing a ZIP archive manager.
1. Navigate to [https://www.7-zip.org/](https://www.7-zip.org/).<br/>
2. Click here.
![image](https://user-images.githubusercontent.com/110630690/211146074-10dc97a8-a810-4f4e-bba4-cd96ffe57581.png)
3. Save it in your workspace folder.
4. Open it.
5. Click Install.
![image](https://user-images.githubusercontent.com/110630690/211146119-13f68a2d-aff5-4864-b534-6957d6a54870.png)

## c. Downloading ModCoderPack
1. Navigate to [https://modcoderpack.com/](https://modcoderpack.com/).<br/>
2. If it says the connection to this website is not secure, that's normal. Their SSL certificate has simply expired. But since we don't have to enter any credentials it's secure.<br/>
3. Click on the link of this file.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/211144821-03c978f6-a4d0-4314-a6ec-c94d1d77fa16.png)<br/>
4. Save it.<br/>

## d. "install" ffmpeg
1. Download this file [FFMPEG](https://www.gyan.dev/ffmpeg/builds/packages/ffmpeg-2023-01-04-git-4a80db5fc2-full_build.7z)<br/>
2. Save it in a new folder inside the folder we created earlier.<br/>
![image](https://user-images.githubusercontent.com/110630690/211145036-f96a1702-1209-4462-86dd-9c8576cbc159.png)
<br/>(Create a new folder)

![image](https://user-images.githubusercontent.com/110630690/211145065-392f096e-fc3e-4d28-bd87-2e5ff5e29e47.png)
<br/>(Enter a name)<br/>

![image](https://user-images.githubusercontent.com/110630690/211145076-45eaef08-8711-42cc-9828-de5993a1023f.png)
<br/>(Naming it FFMPEG)<br/>

![image](https://user-images.githubusercontent.com/110630690/211145160-5e4b997c-dc19-4733-ace7-42a855ccebfd.png)
<br/>(Placing the file inside the folder)<br/>

![image](https://i-am-a.fuchsiax.dev/and-i-skid/2648haf2v6csaqh.gif)
<br/>(Extracting a folder from the file)<br/>

![image](https://i-am-a.fuchsiax.dev/and-i-skid/nzsuywpjz42kfd4.gif)
<br/>(Moving all the file in bin inside that new folder to the FFMPEG directory and deleting the folder)<br/>

## e. Saving the minecraft 1.8.8 JAR.
1. Navigate to [https://mcversions.net/download/1.8.8](https://mcversions.net/download/1.8.8).<br/><br/>
![image](https://i-am-a.fuchsiax.dev/and-i-skid/2uuocbwczdpuvxm.gif)<br/>
2. Click "Download Client JAR".<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/211145483-d0f1b53a-bb6f-448b-bca6-42ca8b2133d2.png)
3. Save it in a new folder inside of the workspace.<br/><br/>
![image](https://i-am-a.fuchsiax.dev/and-i-skid/6diiao69hlval23.gif)
4. Rename the file into ```1.8.8```.<br/><br/>
![image](https://i-am-a.fuchsiax.dev/and-i-skid/3hyyt78op6nmmd3.gif)

## f. Getting assets index for 1.8.
1. Launch minecraft java edition in 1.8.8.
2. Close minecraft.
3. Press Win+R and type in ```%appdata%```.<br/><br/>
![image](https://i-am-a.fuchsiax.dev/and-i-skid/qzmra8f3u4qi8y3.gif)<br/>
4. Navigate into the ```.minecraft``` folder then inside of ```assets``` and finally inside ```indexes```.<br/><br/>
![image](https://i-am-a.fuchsiax.dev/and-i-skid/ogmyvqwp06jkezp.gif)<br/>
5. Copy the file.
6. Paste it inside the Minecraft JAR folder in the workspace.
![image](https://i-am-a.fuchsiax.dev/and-i-skid/ax6m290cv3cklj0.gif)

## g. Installing java
1. Navigate to [https://adoptium.net/temurin/releases/?version=11](https://adoptium.net/temurin/releases/?version=11). You should arrive to a webpage that looks like this.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210970740-91ed3996-55a8-45a2-8b29-07d2716590a2.png)<br/>
2. You are prompted to enter your operating system and the architecture.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210971197-175190f5-f0e4-4cfb-81bc-c59a91db395e.png)<br/>
3. After entering our device's details, it should be similar to this.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210971386-4ef0ca26-55e7-4b8a-af32-df8b8b183a44.png)<br/>
4. At the end of the webpage you should see all the installations that suit your device.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210971569-71611ec0-d0ef-4acd-a4c6-6c3dc6338c07.png)<br/>
5. We will download the .msi file since it does all the installation process for us.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210971813-4988ec32-abe3-4c6b-934f-fa60cb1453e1.png)<br/>
6. Wait for the download to finish. It should take a while since it's a big file.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210972236-6af3146b-7540-4570-a1ee-270db190491d.png)<br/>
7. Open the file. The installer looks like this.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210974500-6a1cb355-2d62-46ef-b6bf-1ecb29123e81.png)<br/>
8. Click next.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210974658-f8fea9b8-61a4-4cda-b25b-9a50d052a0df.png)<br/>
9. We want to enable this.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210974858-e501f79c-d103-4697-a267-eb510a52a5b3.png)<br/>
10. Click on the X icon next to it. It will open a little menu. From there, select "Will be installed on hard drive".<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210974985-a8b09257-ab97-4dad-8eca-7974634e93fe.png)<br/>
11. Click next again.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210975169-21cd28b6-31dd-498d-82b4-c09aed5b3735.png)<br/>
12. Press ![image](https://user-images.githubusercontent.com/110630690/210975322-9e49dec7-6b98-4be6-9ca5-3b7527d174cb.png)<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210975248-62540ad3-9e6e-4874-a9c0-ad3297c68862.png)<br/>
<br/>
Congrats you successfully installed java! To test it out, open a command prompt.<br/><br/>

![image](https://user-images.githubusercontent.com/110630690/210975640-baadffc7-fbe4-4b5b-b752-ec5ec36759c9.png)
<br/><br/>
Type in ```java --version```<br/><br/>

![image](https://user-images.githubusercontent.com/110630690/210976854-1aa55738-2aea-4712-ba3c-dfe66d8d9b91.png)<br/>

You will see this appear if java is installed.<br/><br/>
![image](https://user-images.githubusercontent.com/110630690/210978227-59c21608-e72f-4e4d-b039-230b2acd9f12.png)<br/>

## h. Installing Eclipse IDE.
1. Navigate to [https://www.eclipse.org/](https://www.eclipse.org/) and click on download.<br/><br/>
![image](https://i-am-a.fuchsiax.dev/and-i-skid/g6ot13hjh3lv172.gif)<br/>

This is all for today's tutorial.
