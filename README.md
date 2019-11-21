# Prochain Substrate Group Logos
A repository of group logos using prochain-substrate

### Adding new group logos

- Create a pull request adding your logo to the correct blockchain in the "groups.json" file

- **Fill out all of the fields, they are all required**

- Add your logo to the /logos/ folder ( **.png format only!** ). Make sure logo's filename matches the field that you specified in the JSON.
- A recommended image size of 160*160,margin 20px,logo with white background   

```
{
  "name":"",         // This is the unique name of your group, it should be case sensitive
  "symbol":"",     
  "description":"",  // Short description of your group
  "url":"",          // The URL to your website, or it's landing page
  "hasimage":"1",    // Adding this specifies that you have added a logo to the /logos/ directory.
}
```


### 添加新的Group Logo

- 请在"groups.json"文件加入Logo相关信息，并创建一个pull request

- **json中的所有字段都是必填项**

- 将logo图片文件加入/logos/文件夹（**只允许.png格式**），且logo的文件名符合json中'name'所写对应项
- 建议图片尺寸160*160,边距20px,背景透明,logo用白色填充
  ![image](https://github.com/ProChain/prochain-substrate-logos/raw/master/logos/example.png)
- 

```
{
  "name":"",         // 这是group的唯一不重复名称，大小写敏感
  "symbol":"",       
  "description":"",  // 对group的简要描述
  "url":"",          // 指向group网站的URL，或指向落地页
  "hasimage":"1",    // 填入1表明已经将图片加入了/logos/文件夹
}
```

