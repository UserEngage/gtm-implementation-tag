# Official User.com Tag for Google Tag Manager

#### This tag will implement User.com on your Website.

https://user.com/en/integrations/custom-script/


Tag will allow you to:

- Send basic analytics to your User.com app
- Display User.com Chat Widget
- Track Users behaviour
- Update User data in User.com app
- Change Chat Widget visibility

User.com | Implementation Tag is also essential for other User.com Tags to work:

- User.com | UE Methods
- User.com | Userengage Methods


### Configuration

Required configuration data:

- **API Key**
	- Find it in your Application -> Settings -> Setup & Integrations
- **Application Domain**
	- Find it in your Application -> Settings -> Setup & Integrations


Optional configuration data

- **User Attributes**
	- Initialising our Script, you can pass User data in this section
	- Undefined values will not be passed
	- Attribute names should have all blank spaces replaced with _ sign
- **Widget Icon Visibility**
	- This settings will overwrite User.com application settings regarding Widget Icon Visibility
	- Keep it as Not Set -- to let User.com application decide when Widget Icon should be visible
- **Console Logs**
	- Select to enable debug console logs.
	- Selection will enable logs in both Preview and Published containers
- **Widget Ready Callback**
	- Select to send a Data Layer Event when User.com script is initialised
	- Use this option to trigger other User.com Tags when the Implementation is not loaded yet on Page Visit
    - Deafult Event Name is Widget Ready. You can overwrite it in the Input Field
