# atmProjectZip
zip of the project

The project pulls innformation of an .xlsx file as a database

![image](https://github.com/user-attachments/assets/5c270cf3-31df-429c-b168-9975ac81a830)

those are the possible NIPS for access

step 1
-unzip the file in the directory of your choosing, the project was build with vite+react

step 2:
run the following commnads first
-npm install
-npm install file-saver
-npm install react-router-dom
-npm install xlsx            
it is posible that the xlxs fails to install properly, in that case substitute the code in file vite.congig.ts with the following:

import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

export default defineConfig({
  plugins: [react()],
  assetsInclude: ['**/*.xlsx']
})


step 3: run the prgram with the following command:
-npm run dev                 


if you have any other questions please let me know and enjoy!
