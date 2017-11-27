<div align="center">
	<h1> File Manager </h1>
</div>

<div align="center">
	<a href="#changelog">
		<img src="https://img.shields.io/badge/stability-stable-green.svg" alt="Status">
	</a>
	<a href="#changelog">
		<img src="https://img.shields.io/badge/release-v1.0.2-blue.svg" alt="Version">
	</a>
	<a href="#changelog">
		<img src="https://img.shields.io/badge/update-november-yellowgreen.svg" alt="Update">
	</a>
	<a href="#license">
		<img src="https://img.shields.io/badge/license-MIT%20License-green.svg" alt="License">
	</a>
</div>

This tool has been created in order to create backups, update files or extract
 specific files from a web application using Windows Server as a platform.

<a name="started"></a>
## Getting Started

This page will help you get started with File Manager.

<a name="requirements"></a>
### Requirements

  * Microsoft Windows Server 2003 or later
  * [Windows Server 2003 Resource Kit Tools](https://www.microsoft.com/en-us/download/details.aspx?id=17657)
  (Only Server 2003)

<a name="installation"></a>
### Installation

  * This file don't require installation

<a name="deployment"></a>
## Deployment

  * This project works with the MVC (Model View Controller) Design Pattern
	* 'Process' file (Model)
    * 'Launcher' file (View)
    * 'Dialog' file (Controller)
  * The Controller File send a JSON Object to Model File with the data
  * Description of the JSON Object:
    * "Function Name": {
							"Source Folder": ,
							"Destination Folder:" ,
							"Custom Folder": ,
							"OS Version":
						}
  * A catalog file and a log of the processes performed are created
  * Special characters can not be processed by the command line, e.g.:
    * "(", ")", "[", "]", """, etc.

<a name="changelog"></a>
## Changelog

**1.0.3** (11/26/2017)

  * <table border="0" cellpadding="4">
		<tr>
			<td><strong>
				Requirements:
			</strong></td>
			<td>
				Windows Server 2003, Windows Server 2008, Windows Server 2012
				and Windows Server 2016
			</td>
		</tr>
		<tr>
			<td>
				<strong>Changes:</strong>
			</td>
			<td>
				<ul>
					<li>
						Better documentation
					</li>
					<li>
						Adjustment of the JSON object
					</li>
				</ul>
			</td>
		</tr>
	</table>

<a name="Donating"></a>
## Donating

If you want to help me to continue this project, you might donate via PayPal.

<a href="https://paypal.me/ManuelFGil"><img src="https://img.shields.io/badge/donate-PayPal-blue.svg" alt="Donate via PayPal"></a>

<a name="authors"></a>
## Authors

  * **Manuel Gil** - *Initial work* - [ManuelGil](https://github.com/ManuelGil) 

See also the list of [contributors](https://github.com/ManuelGil/File-Manager/contributors)
 who participated in this project.

<a name="license"></a>
## License

File Manager is licensed under the MIT License - see the
 [MIT License](https://opensource.org/licenses/MIT) for details.
