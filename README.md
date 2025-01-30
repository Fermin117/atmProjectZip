# atmProjectZip
zip of the project

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
