# Getting Started with your Lab
 
## Accessing Your Lab Environment
 
Once you're ready to dive in, your virtual machine and guide will be right at your fingertips within your web browser.

## Exploring Your Lab Resources
 
To get a better understanding of your lab resources and credentials, navigate to the **Environment** tab.

   ![](./images/env.png)

## Utilizing the Split Window Feature
 
For convenience, you can open the lab guide in a separate window by selecting the **Split Window** button from the Top right corner.

   ![](./images/splittt.png)

## Managing Your Virtual Machine
 
Feel free to **Start, Restart,** or **Stop (2)** your virtual machine as needed from the **Resources (1)** tab. Your experience is in your hands!

   ![](./images/vmssr2.png)

## Access DSP Files on Linux VM

Follow these steps to access and use DSP files on your Linux virtual machine:

### Check Available Files

```bash
ls /opt/dsp-files
```
### Copy Files to Home Directory

```bash
cp -r /opt/dsp-files ~/
sudo chown -R $USER:$USER ~/dsp-files
```
You can now access and use the DSP files from your home directory as needed.

## Support Contact

The CloudLabs support team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both learners and instructors, ensuring that all your needs are promptly and efficiently addressed.

Learner Support Contacts:

- Email Support: labs-support@spektrasystems.com
- Live Chat Support: https://cloudlabs.ai/labs-support
