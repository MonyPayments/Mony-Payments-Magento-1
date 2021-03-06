<h2> 1.1 New Mony Installation </h2>
<p>This section outlines the steps to install the Mony plugin for the first time.</p>

<p> Magento can be installed in any folder on your server however for the purposes of this document, [MAGENTO] will refer to the root folder where you have installed your version of Magento. </p>

<ol>
<li> The Mony Magento plugin will be provided to you as a zip file or tar file </li>
<li> Unzip the file and follow the instructions to copy across the files Code Directory </li>
<li> Copy all files in /app/code/community/Mony folder from the unzipped plugin into [MAGENTO]/app/code/community/Mony directory </li>
<li> Copy all files in /design/frontend/base/default/layout to [MAGENTO]design/frontend/base/default/layout </li>
<li> Copy all files in /design/frontend/base/default/template to [MAGENTO]design/frontend/base/default/template </li>
<li> Copy all files in /design/adminhtml/default/template to [MAGENTO]design/frontend/base/default/template JS Directory </li>
<li> Copy all files in /js folder into [MAGENTO]/js </li>
<li> Login to Magento admin and go to System > Cache Management </li>
<li> Flush the Magento cache by selecting “Flush Magento Cache” </li>
<li> Check that the correct Mony version has been installed and then complete the Configuration steps outlined in this document </li>
</ol>

<h2> 1.2	Mony Configuration </h2>
<p> This configuration steps for the plugin are described in the remainder of this document. </p>

<ol>
<li> Check the version of the plugin that has been installed </li>
<li> Obtain a Merchant ID, Merchant Number and Secret Key from Mony </li>
<li> Configure the Mony payment methods </li>
<li> Place an order on your site using the test details provided </li>
</ol>

<h2> 1.3	Upgrade of Mony Installation </h2>
<p> This section outlines the steps to REMOVE the existing plugin before the upgrade.
Remove the Mony plugin by manually deleting the following Mony folders and Mony files. </p>
<ol>
<li> Login to Magento admin and go to System > Cache Management </li>
<li> Flush the Magento cache by selecting "Flush Magento Cache" </li> 
<li> Check that the correct Mony version has been installed </li>
</ol>