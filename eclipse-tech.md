
## [What's New in Kepler](http://127.0.0.1:64767/help/index.jsp?topic=%2Forg.eclipse.platform.doc.isv%2FwhatsNew%2Fplatform_isv_whatsnew.html&cp=2_2)

SWT Changes 

XULRunner on 64-bit Windows

The browser widget now supports the embedding of XULRunner on Windows x86_64.



http://www.eclipse.org/swt/faq.php#whatisbrowser

> Note: As of Eclipse/SWT 4.3 a user can specify a comma-separated list of native renderers, in order of preference, for the org.eclipse.swt.browser.DefaultType value. Additionally, "ie" is now a valid native renderer value. The purpose of these changes is to enable applications to specify the default use of either Mozilla or WebKit on non-Windows platforms (where conflicting dependent library problems can occur) without affecting the default renderer that is used on Windows (IE). An application wishing to do this should set this property's value to either "ie,webkit" or "ie,mozilla". On Windows this will leave SWT.NONE-style Browsers to use IE, and on other platforms where IE is not available the second specified renderer in the list will be used for SWT.NONE-style Browsers.

> The best opportunity for a user to set this property is by launching their application with a -D VM switch (eg.- add to the end of the eclipse.ini file: -Dorg.eclipse.swt.browser.DefaultType=webkit). 


Q: Can I specify which Mozilla profile gets used?

> A: (@since 4.4) A profile can be specified for use by all Mozilla-based Browser instances by setting Java property org.eclipse.swt.browser.MOZ_PROFILE_PATH to the path of the profile before the first instance of a Mozilla-based Browser is created. The best opportunity for a user to set this property is by launching their application with a -D VM switch (eg.- add to the end of the eclipse.ini file: -Dorg.eclipse.swt.browser.MOZ_PROFILE_PATH=...). 



http://wiki.eclipse.org/How_to_report_a_deadlock






