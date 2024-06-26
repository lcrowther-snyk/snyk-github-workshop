# Snyk GitHub Workshop

The following workshop is designed to show how Snyk integrates into SCM systems like GitHub and performs various application security scans and what fix/remediation advice is given to secure you applications during the SDLC.

## Prerequisites

* public GitHub account - http://github.com
* snyk CLI - https://support.snyk.io/hc/en-us/articles/360003812538-Install-the-Snyk-CLI

## What we will do in this hands-on workshop?

TODO:// Pas

# Workshop Steps

_Note: It is assumed your using a mac for these steps, but it should also work on Windows or linux with some modifications to the scripts potentially_

## Step 1 - Fork our sample repo into your own GitHub account

Navigate to the following GitHub repo - https://github.com/papicella/tictactoe

* Click on the "**Fork**" button
* Ensure you are forking this repo to your public GitHub account
* Click done

![alt tag](https://i.ibb.co/Wpgv6kn/GH-workshop-1.png)

## Step 2 - Configure GitHub Integration

_NOTE: You may have already setup GitHub integration in that case go ahead and skip this step_

* Login to http://app.snyk.io Sign up if you haven't already.
* Navigating to Integrations -> Source Control -> GitHub
* Fill in your Account Credentials to Connect your GitHub Account.

![alt tag](https://i.ibb.co/0qmpjYT/platform-workshop-2.png)

Now let's enable Code scanning you do that as follows

* Select Settings -> Snyk Code -> Enable Snyk Code checkbox -> Save Changes

![alt tag](https://i.ibb.co/4gHzt3d/GH-workshop-3.png)

Now that Snyk is connected to your GitHub Account, import the Repo into Snyk as a Project.

* Navigate to Projects menu option
* Click "**Add Project**" then select "**GitHub**"
* Click on the Repo you forked
* Once done (about 3 minutes) you should see something similar to this


## Congratulations - Workshop Completed!!!

Thanks for attending and completing this workshop

![alt tag](https://i.ibb.co/qJFDfWP/snyk-thumb.jpg)

<hr />
Shilpa Raghunathan [shilpa.raghunathan at snyk.io] is a Staff Partner Solutions Engineer APJ at Snyk
Pas Apicella [pas at snyk.io] is a Principal Solution Engineer APJ at Snyk