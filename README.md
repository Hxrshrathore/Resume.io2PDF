# resume.io2pdf

A program that allows users to download their resumes from [resume.io](https://resume.io/) as PDFs, including links.

## Usage

```bash
./resumeio2pdf [options] [ID or URL]
./resumeio2pdf https://resume.io/r/SecureID
```

Options:
*  `-pdf` (string)  name of pdf file (default: `SecureID` + `.pdf`)
*  `-sid` (string) SecureID of resume
*  `-url` (string) link to resume of the format: https://resume.io/r/SecureID
*  `-verbose` show detailed information
*  `-version` show version
*  `-y`	overwrite PDF file

## Quick Instructions
1. Run `go build` to generate the executable.
2. Run `./resumeio2pdf https://resume.io/r/[SecureID]` where the provided URL is that generated by the **Share Link** on resume.io.

## Step-by-Step Instructions
1. Download the application by clicking the **<> Code** button and choosing **Download ZIP**.
 
2. Once the download has been completed, extract the files. You will end up with a **resumeio2pdf-main/** folder.

3. Open your terminal and navigate to the **resumeio2pdf-main/** folder that you have just extracted.
- You may have the option to skip this by simply choosing the **New Terminal at Folder** after right-clicking on the folder.

4. With your terminal still open, type the command `go version` to see if you already have Go installed.
- If you get a message with version information that looks something like `go version go1.17.6 …` then you can skip to Step 6.
- Otherwise, continue on to the next step.

5. Open your web browser and navigate to the [Go Downloads Page](https://go.dev/dl/) and choose your operating system from the **Featured Downloads** section. Download the package and follow the installation instructions.
- Upon completion, restart your terminal and navigate back to the **resumeio2pdf-main/** folder. You should now see version information after typing in the `go version` command. If you have issues with this step, visit the [Download and Install Page](https://go.dev/doc/install) for the official instructions. 

6. With Go installed, you can now run the `go build` command to build the executable file that will download your PDF.
- A successful build will not display any confirmation in the terminal. However, you can check the files in the **resumeio2pdf-main/** folder to confirm that the command has generated a **resumeio2pdf** executable file. 
- If you received an error in the terminal, make sure you are still in the **resumeio2pdf-main/** folder before running the command. Otherwise, trace back through the above steps and give it another shot.

7. Finally, you can run the `./resumeio2pdf https://resume.io/r/[SecureID]` where the provided URL is that generated by the **Share Link** on resume.io. When the process is complete, you will receive a message in the terminal that your file has been stored as **\[SecureID].pdf**. Check the **resumeio2pdf-main/** folder for your file.



## Other Questions and Concerns
* I don't understand how to install and/or use Go.
* Can you download my resume for me? 
* Can you make a video tutorial?

Please visit the [pricing page on Resume.io](https://resume.io/pricing) which provides fair and affordable prices for this service, including an easy method of downloading your resume without the use of this software.
