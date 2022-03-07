# Creative SDK Content Management, Workflow, Authentication Component - End of Support FAQs

## Which Creative SDK components will no longer be supported?

The Creative SDK Content Management, Workflow, and Authentication components for iOS, Android, and Web are no longer supported. More specifically, we are ending support for the following features within the Creative SDK components: Asset Browser UI, CC Files API, CC Libraries API, Lightroom Photos API, Typekit (Fonts) UI, PSD file type read/write, AI filetype write, Send to Desktop, and Authentication.

## Why is Adobe ending support for the Creative SDK Content Management, Workflow, and Authentication components?

Adobe is improving the underlying platform and APIs that power the Creative SDK. In the best interest of the developer community and end users, we want to offer a set of APIs and developer products that have longevity, stability, ongoing support, and alignment with the direction of Creative Cloud.

## Does this mean that my Creative SDK integration will stop working?

No. Integrations of the Creative SDK Content Management, Workflow, and Authentication components will continue to work. At this point, there are no plans to shut down core services behind these Creative SDK components.

## What does “ending support” mean?

We will no longer be making feature additions or enhancements to the Creative SDK. With that, we are no longer providing developer support for Creative SDK integrations, nor are we accepting Production Mode ID requests for Creative SDK developers.

As mentioned above, integrations should continue to work, however, we do not encourage developers to start working on new Creative SDK integrations or enhance existing integrations of the Creative SDK. Over the coming months, we will be removing public resources, including Creative SDK documentation, Creative SDK support center, and SDK downloads.

## Does Adobe provide an alternative to the Creative SDK Content Management, Workflow, and Authentication components?

At this point, we are not offering an alternative to the Creative SDK’s Asset Browser UI, CC Files API, CC Libraries API, Lightroom Photos API, PSD file type read/write, AI filetype write, and Send to Desktop. We are working on new APIs that will serve as an alternative to some of the Creative SDK features.

There is an alternative to the Typekit Browser UI through the [Adobe Fonts platform](https://www.adobe.io/apis/creativecloud/adobe-fonts.html).

Authentication capabilities will continue to be available through the publicly documented [authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/) endpoints and the Creative SDK scopes.
