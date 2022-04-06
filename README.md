# Official User.com Tag for Google Tag Manager

https://user.com/en/integrations/custom-script/


#### This tag will implement User.com on your Website.

User.com plugins work by injecting a script to your website which enables the communication between your site and our API.



Features:

- Send basic analytics to your User.com app
- Display User.com Chat Widget
- Track Users behaviour
- Update User data in User.com app
- Change Chat Widget visibility

User.com | Implementation Tag is also essential for other User.com Tags to work:

- User.com | UE Methods
- User.com | Userengage Methods


#### Configuration

##### Required configuration data

- **API Key**
	- You can find it in your **Application -> Settings -> Setup & Integrations**
- **Application Domain**
	- You can find it in your **Application -> Settings -> Setup & Integrations**


##### Optional configuration data

- **User Attributes**
	- Pass data to update standard and custom User attributes
	- Provide standardized User attributes without blank characters, i.e. Do not use First Name, use first_name instead
	- Undefined attribute values will not be passed
- **Widget Icon Visibility**
	- This settings will overwrite User.com application settings regarding Widget Icon Visibility
	- If you **do not** want to overwrite User.com application settings, choose the **--** option
- **Console Logs**
	- Select to enable debug console logs.
	- Selection will enable logs in both Preview and Published containers
- **Widget Ready Callback**
	- Select to send a Data Layer Event when User.com script is initialised
	- Use this option to trigger other User.com Tags when you cannot use the standard Page Visit trigger, i.e. User.com is not loaded yet
    - Deafult Event Name is Widget Ready. You can overwrite it in the Input Field
