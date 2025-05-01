# How to Automatically Add Case Number to Calendly Meetings
### When customers click your Calendly link and schedule a meeting, the case number will automatically be appended to the meeting title in your calendar
1. Log in to **[Calendly](https://calendly.com/event_types)** and edit your **Event type**
2. Click **Notifications and workflows**, then **Calendar invitation**
3. In the **Title** section, edit your meeting title
   1. Add a variable: click **Variables** and choose **UTM Source**
   2. You can also add other variables, such as **My Name**
   3. For example: Cloud Support Case #`UTM Source` - Meeting with `My Name`
4. Click **Save and close**
5. In a case email, type your Calendly event URL and append the following: `?utm_source={{{Case.CaseNumber}}}`
   1. For example: `https://calendly.com/tttalexr/cloud-support-meeting?utm_source={{{Case.CaseNumber}}}`
6. Optional: Create a snippet in [Text Blaze](https://blaze.today) with the link

> [!WARNING]
> If you add this to your [Salesforce signature](../signatures/README_Signatures.md), be mindful of the character limit. You can shorten your Calendly URL by editing the **Event type** and going to **Booking page options**. You may wish to clone your Event type first to avoid invalidating existing links.