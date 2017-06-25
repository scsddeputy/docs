Login Handlers
=======

Mixer
---------------

You can allows users to sign in on your community with their Mixer account. This is a great way to make it easier for users to get started on your community and increase the number of signups, especially if the subject of your community means your users are likely to have Mixer accounts. This guide covers everything you need to know to set up this integration.

### Create OAuth App

-1. Visit [Mixer Lab >](https://mixer.com/lab) and sign in with your Mixer account if not already signed in.

-2. Click the OAuth Clients Link under the logo

![Image of Client Link](https://i.imgur.com/Vy0mnsz.png)

-3. Click the + button to create a new App.

![Image of button](https://i.imgur.com/p5XQqbS.png)

-4. Fill in the form with your community information

![Image of form](https://i.imgur.com/Q2de3c8.png)

- Name can be anything you want (Will show on the Authorize Page)
- Website is the redirect url for your site and should be filled out as shown: http://your-url.com/applications/core/interface/mixer/auth.php. Replace 'your-url' with the address of your community. If you use https, change it in the url to https.
- You MUST check the 'Use secret key' box or you will not be provided a client secret key

-5. Click the 'Create Client' Button at the bottom of the form.

-6. Keep this page handy as you will need it in the Link with Site Step.

### Install Plugin

-1. Upload all contents of the Upload folder to your IPS 4 Root Folder

-2. Install the plugin file. Go to your Admin CP->System->Plugins->Install New Plugin and select the Mixer Login.xml file.

### Link with Site

-1. Now that you have your Client ID and Client Secret, go to your Admin Panel->System->Login Handlers and click the pencil (Edit) on the Mixer login method. Copy and paste the Client ID and the Client Secret and then Save.

![Image of keys](https://i.imgur.com/1XxDvKu.png)

-2. Once you have done this, you can now enable the login method and you can test. 

Smashcast
---------------

You can allows users to sign in on your community with their Smashcast account. This is a great way to make it easier for users to get started on your community and increase the number of signups, especially if the subject of your community means your users are likely to have Smashcast accounts. This guide covers everything you need to know to set up this integration.

### Create OAuth App

-1. Visit [Smashcast TV >](https://smashcast.tv) and sign in with your Smashcast account if not already signed in.

-2. Go to your Account Settings Page by clicking the icon at the top right with your avatar. In the drop down, click settings.

![Image of keys](http://i.imgur.com/gabpgK1.png)

-3. On the left side of the settings page, in the menu click on Connections.

![Image of keys](http://i.imgur.com/RjyfEtc.png)

-4. Scroll to the bottom of the page and click the Register your application button.

![Image of keys](http://i.imgur.com/v6erMWt.png)

-5. Fill in the form with your community information

![Image of keys](http://i.imgur.com/ibp1HG5.png)

- Application Name can be anything you want (Will show on the Authorize Page)
- Redirect URI is the redirect url for your site and should be filled out as shown: http://your-url.com/applications/core/interface/smashcast/auth.php. Replace 'your-url' with the address of your community. If you use https, change it in the url to https.

-6. Click the 'Create' Button at the bottom of the form.

-7. Keep this page handy as you will need it in the Link with Site Step.

### Install Plugin

-1. Upload all contents of the Upload folder to your IPS 4 Root Folder

-2. Install the plugin file. Go to your Admin CP->System->Plugins->Install New Plugin and select the Smashcast Login.xml file.

### Link with Site

-1. Now that you have your Token and Secret Keys, go to your Admin Panel->System->Login Handlers and click the pencil (Edit) on the Smashcast login method. Copy and paste the Token and the Secret and then Save.

![Image of keys](http://i.imgur.com/p9inmOh.png)

-2. Once you have done this, you can now enable the login method and you can test. 
