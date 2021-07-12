# mLab School ID Whitelisting process

To whitelist school Id's on mLab chrome plugin application

- First, we grab the list of School Id's in spreadsheet
- Clean the the data
  - Make sure there is no empty school Id
  - Remove duplicated school Id's
- Go to UNICEF Azure backend
- Select the mLab container
- Add the list of school Id's to the configuration file
- Restart mLab container (MANDATORY!)
- Test
  - Pick one newly added school Id and try to send data from the plugin

<img src="images/mLab_config.JPG.jpg" />
