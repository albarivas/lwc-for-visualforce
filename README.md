# Lightning Web Components for Visualforce

Examples of how to use Lightning Web Components inside Visualforce pages

1. If you haven't already done so, authorize with your hub org and provide it with an alias (myhuborg in the command below):

`sfdx force:auth:web:login -d -a myhuborg`

2. Create a scratch org and provide it with an alias (lwc-for-visualforce in the command below):

`sfdx force:org:create -s -f config/project-scratch-def.json -a lwc-for-visualforce`

3. Push the app to your scratch org:

`sfdx force:source:push`

4. Assign the lwc_for_visualforce permission set to the default user:

`sfdx force:user:permset:assign -n lwc_for_visualforce`

1. Open the scratch org:

`sfdx force:org:open`
