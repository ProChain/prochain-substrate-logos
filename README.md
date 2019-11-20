# Prochain Substrate Token Logos
A repository of token logos using prochain-substrate

### Adding new token logos

- Create a pull request adding your logo to the correct blockchain in the "apps.json" file

- **Fill out all of the fields, they are all required**

- Add your logo to the logos/ folder ( **.jpg .jpeg .png format only!** ). Make sure logo's filename matches the field that you specified in the JSON.

```
{
  "name":"",         // This is the unique name of your token, it should be case insensitive
  "description":"",  // Short description of your application.
  "url":"",          // The URL to your token website, or it's landing page.
  "hasimage":"1",    // Adding this specifies that you have added a logo to the /logos/ directory.
}
```
