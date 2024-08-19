# WebSSOProfileImpl.java override

Use this repo as a baseline to override the built-in WebSSOProfileImpl.java

Once deployed, add `com.liferay.saml.opensaml.integration.internal.servlet.profile.WebSsoProfileImpl` to components blacklist.

Only override Liferay's built-in implementation if there is no other option as this will be expensive to you from a maintenance perspective.

Make feature requests against Liferay if you need new capability.
