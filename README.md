# Prochain Substrate Group Logos
A repository of group logos using prochain-substrate

### Adding new group logos

- Create a pull request adding your logo to the correct blockchain in the "groups.json" file

- **Fill out all of the fields, they are all required**

- Add your logo to the /logos/ folder ( **.jpg .jpeg .png format only!** ). Make sure logo's filename matches the field that you specified in the JSON.

```
{
  "name":"",         // This is the unique name of your group, it should be case insensitive
  "symbol":"",       // The unique symbol of your group
  "description":"",  // Short description of your group
  "url":"",          // The URL to your website, or it's landing page
  "hasimage":"1",    // Adding this specifies that you have added a logo to the /logos/ directory.
}
```


### 添加新的Group Logo

- 请在"groups.json"文件加入Logo相关信息，并创建一个pull request

- **json中的所有字段都是必填项**

- 将logo图片文件加入/logos/文件夹（**只允许.jpg .jpeg .png格式**），且logo的文件名符合json中'name'所写对应项

```
{
  "name":"",         // 这是group的唯一不重复名称，大小写不敏感
  "symbol":"",       // Group的唯一symbol
  "description":"",  // 对group的简要描述
  "url":"",          // 指向group网站的URL，或指向落地页
  "hasimage":"1",    // 填入1表明已经将图片加入了/logos/文件夹
}
```

