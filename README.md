# TinkerWithAI_Git
Repo to be used for the Tinker with AI GIT Session at UTSA


# Instructions for creating an account and service account key on Google Cloud Platform
In the Cloud Console, go to the Create service account page (https://console.cloud.google.com/projectselector/iam-admin/serviceaccounts/create?supportedpurview=project&_ga=2.188472298.315380980.1621963846-832071502.1621963846&_gac=1.205128228.1621963865.EAIaIQobChMIwNLslK7l8AIVGm5vBB2nLAsmEAAYASAAEgIlC_D_BwE)

Select a project.
In the Service account name field, enter a name. The Cloud Console fills in the Service account ID field based on this name.

In the Service account description field, enter a description. For example, Service account for quickstart.

Click Create.
Click the Select a role field.

Under Quick access, click Basic, then click Owner.

Note: The Role field affects which resources your service account can access in your project. You can revoke these roles or grant additional roles later. In production environments, do not grant the Owner, Editor, or Viewer roles. For more information, see Granting, changing, and revoking access to resources.
Click Continue.
Click Done to finish creating the service account.

Do not close your browser window. You will use it in the next step.
In the Cloud Console, click the email address for the service account that you created.
Click Keys.
Click Add key, then click Create new key.
Click Create. A JSON key file is downloaded to your computer.
Click Close.
For more information visit https://cloud.google.com/docs/authentication/getting-started

