# How to add a new contract

## Step 1 - Edit contract.md

In the master branch, click on `contract.md` to see the file. Click on the edit button (looks like a pencil)
to start editing this file. You can click the "Preview changes" tab while you are editing to see
a rendered preview of the file. Do not commit yet, see next step.

## Step 2 - Create Pull Request

Once you are done, fill in proper title and description under `Commit changes`.
Next, select `Create a new branch for this commit and start a pull request`.
Now a text box appears to provide a branch name. Fill it in this format:
`<client>-<staff name(s)>-month-year` . Example: `veritrans-emil-kashyap-sep-2015`.
Now click `Propose file change` button to submit a pull request.
See the following screenshot:

![image](https://cloud.githubusercontent.com/assets/1707078/11531375/6d6b15e2-9922-11e5-997d-4c60d20b1342.png)

## Step 3 - Review
Once the PR has been created, it should get reviewed
and approved for sending.

## Step 4 - Deploy and download
Once reviewed, you can proceed to download the converted PDF file.

Fred should auto deploy when the PR is submitted, else,

Go to `notifications` HipChat room and type the following command:

```
# @fred deploy <branchname> of code-mancers/service-agreements
You    | @fred deploy veritrans-emil-kashyap-sep-2015 of code-mancers/service-agreements
Alfred | Deployed veritrans-emil-kashyap-sep-2015 : {"app":{"8000":"http://bold-grass-3399.46.4.126.75.xip.io"}}
```
Click on this URL that fred shared after deploying and download `contract.pdf`.

## Step 5 - Send contract and close Pull Request (do not delete the branch!)
Once you've downloaded the PDF, you can send it to the client.
After it's all done, close the Pull Request, but do not delete the branch.
