# Miro Terms Modal Banner App (Web-SDK V2 & AWS S3)

The Miro Web SDK allows you to extend Miro functionality to customise it based on your company needs. In this guide we will show how to create a custom modal banner on your Miro boards that you can show to your users/attendees with any desired content and/or call to actions.

Using AWS S3 you can host your html files and serve them as regular web pages so they can load within Miro. In addition, you can also use AWS S3 to add custom functionality to your Miro app to track which users have already accepted the modal, so that the modal does not re-appear again for those users. In this guide we will guide you on how to achieve this functionality using Miro and AWS S3.

To find detailed instructions please review the following guide:<br>
[https://drive.google.com/file/d/1OgKzoY8xHb4YEz1eljvHkjuP0M-cKcmz/view?usp=sharing](https://drive.google.com/file/d/1OgKzoY8xHb4YEz1eljvHkjuP0M-cKcmz/view?usp=sharing)

__Important__: this application uses various AWS services and there are costs associated with these services after the Free Tier usage - please see the [AWS Pricing page](https://aws.amazon.com/pricing/) for details. You are responsible for any AWS costs incurred. No warranty is implied in this example.

```bash
.
├── README.MD                   <-- This instructions file
├── webassets                   <-- HTML and JavaScript files for the Miro app
├── getSignedURL                <-- Source code for the serverless backend
```
## Requirements

* AWS CLI already configured with Administrator permission
* [AWS SAM CLI installed](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html) - minimum version 0.48.
* [NodeJS 16.x installed](https://nodejs.org/en/download/)

## Installing the application

For a better understanding on how to set up and install this application please follow the steps on the PDF guide below:<br>
[https://drive.google.com/file/d/1OgKzoY8xHb4YEz1eljvHkjuP0M-cKcmz/view?usp=sharing](https://drive.google.com/file/d/1OgKzoY8xHb4YEz1eljvHkjuP0M-cKcmz/view?usp=sharing)

## Support

If you have any questions or need assistance setting up this application, please reach out to your Miro Customer Success Manager or dedicated Miro Solutions Engineer.
