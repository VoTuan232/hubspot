### Website Url
+ https://app.hubspot.com/
+ https://app.hubspot.com/academy
+ https://app.hubspot.com/design-manager/
+ https://app.hubspot.com/personal-access-key
+ https://developers.hubspot.com/docs/cms/hubl
    - Hubl not program language , it is markup language
    - It's not client side 

### Reference: 
+ https://marketingai.admicro.vn/hubspot-la-gi/
  
### Setup: https://www.youtube.com/watch?v=12fB0pZSPuc
+ Add Folder
+ npm init
+ npm install @hubspot/cms-cli or
+ npm install @hubspot/cms-cli@latest
+ npx hs init
=> auto open url: https://app.hubspot.com/portal-recommend/l?slug=personal-access-key
+ api-key: CiRiMWVmNzVhNi1lY2FhLTQwOWEtODViMi03Yzk3YzA5MjQxNjQQ6sGrCRjplq8LKhkABeaRgtqCbHI8JU_3r84qE8qejCeJCnPF
+ hs create website-theme my-website-theme

### Create, Push , Upload 
+ npx @hubspot/create-cms-project my-website-theme
+ npx hs upload my-website-theme/src my-website-theme : upload src folder from local to remote

### Hubspot CMS
+ File Management: Store Image, Pdf,...