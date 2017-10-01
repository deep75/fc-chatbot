![enter image description here](https://franceconnect.gouv.fr/images/fc_logo_v2.png)

![enter image description here](https://2.bp.blogspot.com/-V3CtS3b1HAc/WWzaWvwJzVI/AAAAAAAABUc/0Od0YddweRUVbOt5OyRbd-6AhJJUwGQ1ACLcBGAs/s1600/Title.png)


## Use Azure app service editor

1. make code change in the online editor

Your code changes go live as the code changes are saved.

## Use Visual Studio Code

### Build and debug
1. download source code zip and extract source in local folder
2. open the source folder in  Visual Studio Code
3. make code changes
4. download and run [botframework-emulator](https://emulator.botframework.com/)
5. connect the emulator to http://localhost:3987

### Publish back

```
npm run azure-publish
```

## Use continuous integration

If you have setup continuous integration, then your bot will automatically deployed when new changes are pushed to the source repository.

![qnabot](https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/images/botframeworkarch.png)



