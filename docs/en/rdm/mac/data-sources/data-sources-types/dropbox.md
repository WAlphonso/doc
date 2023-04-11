---
title: Dropbox
---
<table>
	<tr>
		<td>

![DataSourceDropBoxLarge.png](/img/common/DataSourceDropBoxLarge.png) 
		</td>
		<td>
{{ en.RDM }} for Mac uses the Dropbox API to retrieve a XML file from the configured repository. There is no need to install the Dropbox client on the machine to open the data source. It is also possible to configure more than one Dropbox account on the same machine. 
		</td>
	</tr>
</table>

{% snippet icon.badgeCaution %} 
The Dropbox integration uses the Dropbox SDK, so any features that are exclusive to the Business or Enterprise editions are NOT supported. 
{% endsnippet %}
 
## Highlights 

* This data source can be shared over the Internet between multiple locations 
* The data source supports auto refresh 
* This is a file-based data source, based on the XML data source 
* To avoid data corruption the session list should be modified in one location at a time 
* No need to have the Dropbox client installed to use the Dropbox data source 
* Each Dropbox data source can use a different Dropbox account  

{% snippet icon.badgeWarning %} 
Although it can be shared between multiple locations, there is no conflict management for the configuration. If you share with other users you may get update conflicts and run into issues. This data source type is meant for a single user using multiple computers, not multiple users . 
{% endsnippet %}
 
## Settings 

### Connection 

![Dropbox - Connection tab](/img/en/rdm/mac/clip6046.png) 

{% snippet icon.badgeInfo %} 
{{ en.RDM }} for Mac support the 2-Factor Authentication of Dropbox. When the button Validate with Dropbox is &#32; press and the 2-Factor Authentication is enable in Dropbox, a first box will open and ask for the Dropbox account password. After, a second box will open to enter the security code. The security code can be received by SMS or generated by Google Authenticator. 
{% endsnippet %}
 
<table>
	<tr>
		<th>
OPTION 
		</th>
		<th>
DESCRIPTION 
		</th>
	</tr>
	<tr>
		<td>
Name 
		</td>
		<td>
Name of the data source. 
		</td>
	</tr>
	<tr>
		<td>
Mode 
		</td>
		<td>

Select the mode that is preferred to configure the data source. Select between:  

* Account 
* Local 
		</td>
	</tr>
	<tr>
		<td>
Email 
		</td>
		<td>
Contains the email address associated with the Dropbox account. 
		</td>
	</tr>
	<tr>
		<td>
Validate with Dropbox 
		</td>
		<td>
Validate the email address with the Dropbox account. 
		</td>
	</tr>
	<tr>
		<td>
Dropbox directory 
		</td>
		<td>
Indicate the folder in Dropbox. It should not contains any drive since it&apos;s stored online. Leave it empty to use the default Dropbox root. 
		</td>
	</tr>
	<tr>
		<td>
Filename 
		</td>
		<td>
Indicate the filename used to store the data on the data source. 
		</td>
	</tr>
	<tr>
		<td>
Compress database file 
		</td>
		<td>
Activate this option if you wish to compress your database file. 
		</td>
	</tr>
</table>

### Advanced 

![Dropbox - Advanced tab](/img/en/rdm/mac/clip10147.png) 

<table>
	<tr>
		<th>
OPTION 
		</th>
		<th>
DESCRIPTION 
		</th>
	</tr>
	<tr>
		<td>
Always ask for password 
		</td>
		<td>
Always ask for password when connecting to the data source. 
		</td>
	</tr>
	<tr>
		<td>
Disable reveal password 
		</td>
		<td>
Disable the reveal password feature when a user access this data source. 
		</td>
	</tr>
	<tr>
		<td>
Allow offline mode 
		</td>
		<td>
Allow the data source to be used in Offline mode. 
		</td>
	</tr>
	<tr>
		<td>
Auto refresh 
		</td>
		<td>
Set the interval to use between each automatic refresh. 
		</td>
	</tr>
	<tr>
		<td>
Manage Cache 
		</td>
		<td>

You can clear the output, analyse, repair or delete the cache of your Dropbox. For more information please follow this [link](/rdm/mac/data-sources/manage-cache/) . 
		</td>
	</tr>
</table>

