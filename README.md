At postman import the curl command and then select Basic Auth.

```
curl --location --request POST 'https://manual-api.lambdatest.com/app/upload/realDevice' \
--header 'Authorization: Basic <Access Token>' \
--form 'name="QATestIPA"' \
--form 'appFile=@"/Users/admin/Documents/LTAutomation/Source/iOSApp/QATestApp.ipa"' \
--form 'custom_id="ixigo"'
```

```
Copy the app_url and replace that at .java as well at the .xml file
```

```
Replace username and access token present at the lambda test dashboard
```

```
import the project at intelliJ and run .xml file by right clicking it
```

```
test will be present at the https://appautomation.lambdatest.com/build
```
