####[500 ASSETS](https://github.com/massiveart/sulu-docs/tree/master/system-requirements/500-assets "500 ASSETS")

* 5100 General
* [5200 Data Structuring](https://github.com/massiveart/sulu-docs/tree/master/system-requirements/500-assets/5200_data-structuring.md "5200 Meta Information Management")
* [5300 Asset Management](https://github.com/massiveart/sulu-docs/tree/master/system-requirements/500-assets/5300_asset-management.md "5300 Asset Management")
* [5400 Connections](https://github.com/massiveart/sulu-docs/tree/master/system-requirements/500-assets/5400_connections.md "5400 Connections")
* [5500 Interfaces](https://github.com/massiveart/sulu-docs/tree/master/system-requirements/500-assets/5500_interfaces.md "5500 Interfaces")
* [5600 Security](https://github.com/massiveart/sulu-docs/tree/master/system-requirements/500-assets/5600_security.md "5600 Security")

##![Contacts](https://raw.github.com/massiveart/sulu-docs/master/system-requirements/images/assets.png)5100 General

####![Alpha](https://raw.github.com/massiveart/sulu-docs/master/system-requirements/images/alpha.png)FR-5101 Image Rendering

**Definition:**

The system shall render the required image sizes for the backend GUI (eg. thumbnails or standard previews) immediately after the upload is completed. Content-dependent images sizes shall be rendered after the assignment process. Optionally the system should provide a facitity to render images on demand (on front-end site request).

**Specification:**

1. Generally the system shall provide automatic file conversions into different sizes and formats
1. When the user assigns a image to a content the system shall render the required images sizes according to the underlying site template within a background operation (rendering queue).
1. CMYK-images shall be automatically converted to RGB-images


####FR-5102 Image Croping

**Definition:**

The system shall provide manual image croping functionalities with predefined aspect rates.

**Specification:**

1. The user shall be able to select one of the aspect rates calculated out of all implemented site templates 
1. The system shall display a selection area with the selected aspect rate
1. The user shall be able to change the selection area in size an position while the aspect rate remains unchangeably

####![Alpha](https://raw.github.com/massiveart/sulu-docs/master/system-requirements/images/alpha.png)FR-5103 Copy URL

The system shall provide a function to copy the URL of each rendered image to the clipboard.