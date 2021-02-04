# ExtJS
GPL Versions of Ext JS

Sencha was aquired by IDERA Software and version 6.2.0 was the last GPL version of Sencha. The release of Ext JS version greater than 6.5+ were under Idera's helm and they seemed to have dropped the GPL version.

## Assembly Instructions
The files has been split so that they can be uploaded to github. Use the following command to merge the files back into a zip file

```
git clone https://github.com/SenchaGPL/ExtJS
cd ExtJS
cat ext-6.2.0-gpl-split* > ../ext-6.2.0-gpl.zip
cd ..
unzip ext-6.2.0-gpl.zip
```
You can then delete the original cloned repo

Alternatively, you can download the GPL version directly from Sencha via 
```
wget http://cdn.sencha.com/ext/gpl/ext-6.2.0-gpl.zip
```
