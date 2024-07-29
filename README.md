# pacdora-postman

## Getting Started

To get started you can either fork the collection from [Pacdora's public workspace](https://www.postman.com/pacdora/workspace/pacdora-developers/overview) within Postman or import the collection JSON file from this repo.

### Fork the collection from Pacdora's public workspace

From within the [Pacdora's public workspace](https://www.postman.com/pacdora/workspace/pacdora-developers/overview), fork the Pacdora API collection:

![Fork collection](assets/postman_fork_collection.png)

Enter a name for your fork and select the workspace where it will be created:
![Fork from](assets/postman_fork_from.png)

You can also fork the environment template from the Pacdora Developers Workspace:
![Fork environment](assets/postman_fork_env.png)

### Set your API key

To run requests you'll need to supply your Key pair. If you don't have it, please <a href="mailto:api@pacdora.com">[contact us]</a> to apply, and set it as an [environment variable](https://learning.postman.com/docs/sending-requests/variables/) within your workspace.

To set any environment variable, fork the environment template within the Pacdora public workspace, or create a new envionment within Postman:

![create a new environment](assets/postman_create_new_env.png)

Add your secret key as a variable to the environment and save:

![set key pair](assets/postman_set_key_and_save.png)

Within the collection set it to use the environment you just created:

![set collection environment](assets/postman_set_collection_environment.png)

If your environment is set up correctly, you should see your secret key value if you mouse over the `secret_key` variable in the Token field:

![key pair mouseover](assets/postman_secret_key_mouseover.png)

## Make a test call

You should be ready now to make a test call. An easy first call is to get a list of user-designed projects.

![get project list endpoints](assets/postman_project_list_endpoints.png)

Please set the request parameters and then click the send button to execute this request.

![get project list send](assets/postman_project_list_send.png)

Of course, you can also choose not to pass any parameters, as we have default values for them. They are not mandatory.

![get project list no parameters send](assets/postman_project_list_no_parameters_send.jpeg)

If your environment is set up you'll get the project list as the response to the call:

![get project list response](assets/postman_project_list_response.png)

If you want to make a POST request, please add the parameters in JSON format by clicking on the 'Body' tab in the request. Here are example parameters for exporting user design projects in PDF format:

![export project in pdf send](assets/postman_export_project_in_pdf_request.png)

You'll see the export task id in the reponse:

![export project in pdf response](assets/postman_export_project_in_pdf_response.png)

## Other instructions

- If the request parameter is optional, you can choose not to pass the parameter rather than passing an empty value.
- You can also visit the [API demo](https://apidemo.pacdora.com/index.html). By clicking the red dot with your mouse, a code example will pop up for your reference.

## We want to hear from you

We want to hear how we can make the collection better! Don't hesitate to report here [issues](https://github.com/Pacdora/pacdora-postman/issues) for any bugs you encounter, suggest new features, or share other ideas you have.
