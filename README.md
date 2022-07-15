This is a demo site showing how to use the sar-component. Visit it [here](https://raw.githack.com/hestiaAI/sar-component-example/master/index.html)
# copy of sar-component's documentation:

``` js
/**
 * &lt;sar-form&gt; custom element that helps the user
 * make subject access request by email.
 *
 * Attributes:
 *
 *   lang (optional): String
 *     Determines what language configuration will be
 *     loaded from file /assets/i18n/component-translations.json
 *
 *   collective (optional): String
 *     Id of a project in the wikibase of personaldata io.
 *     If collective is not set, or an empty string,
 *     the option organizationType is used to determine
 *     the targeted organizations
 *     Examples:
 *     - Q5393: the eyeballs
 *
 *   organizationType (optional): String
 *     Id of a company type in the wikibase of personaldata io.
 *     If organizationType is not set, or an empty string,
 *     the list of organizations is loaded from file
 *     /assets/data/sar-organizations.json
 *     Examples:
 *     - Q5066: online dating application
 *     - Q97: transportation network company
 *
 *   mailtoTemplateName (optional): String
 *     Name of a template from personaldata.io
 *     that is used to generate the content of the email.
 *     Default value: MailtoAccess
 *
 *   carbonCopyDescription (optional): String
 *     Label for a checkbox that allows to add a bcc recipient.
 *     If this attribute and carbonCopyRecipient are left empty,
 *     the checkbox is not shown
 *
 *   carbonCopyRecipient (optional): String
 *     Default value for the bcc recipient.
 *     If this attribute and carbonCopyDescription are left empty,
 *     the checkbox to enable bcc is not shown
 *
 * Sample usage:
 *
      &lt;sar-form organizationType="Q5066"
                mailtoTemplateName="MailtoAccess"
                carbonCopyDescription="Send a copy another email address"
                carbonCopyRecipient="bill@microsoft.com"
                lang="en"&gt;
      &lt;/sar-form&gt;
 */
```
