# TinkerWithAI_Git
Repo to be used for the Tinker with AI GIT Session at UTSA



## Install Python libraries
```pip install numpy```

```pip install seaborn```

```pip install bigquery```


```pip install tensorflow```


## Instructions for creating an account and service account key on Google Cloud Platform
In the Cloud Console, go to the Create service account page (https://console.cloud.google.com/projectselector/iam-admin/serviceaccounts/create?supportedpurview=project&_ga=2.188472298.315380980.1621963846-832071502.1621963846&_gac=1.205128228.1621963865.EAIaIQobChMIwNLslK7l8AIVGm5vBB2nLAsmEAAYASAAEgIlC_D_BwE)
Create a project and name it as Tinker_with_AI. Use default for all other settings and click create.
Select the project you created just now.

Click Keys.

Click Add key, then click Create new key.

Click Create. A JSON key file is downloaded to your computer.

Click Close.

For more information visit https://cloud.google.com/docs/authentication/getting-started

# As discussed in the workshop, you will have to create a free account on Google Cloud Platform, enable BigQuery API and create
# a credential file associated with your project. Save this file to your computer. Ensure that the file is in your operating
# systems search path. The name of your file may be different from gcp.json.
# Code to copy for bigquery
import os

credential_path = "gcp.json"
os.environ['GOOGLE_APPLICATION_CREDENTIALS'] = credential_path

