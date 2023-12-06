# PicX

[![Author](https://img.shields.io/badge/author-XPoet-orange.svg)](https://github.com/XPoet)
[![Release](https://img.shields.io/github/release/XPoet/picx.svg)](https://github.com/XPoet/picx/releases)
[![License](https://img.shields.io/github/license/XPoet/picx.svg)](https://github.com/XPoet/picx/blob/master/LICENSE)

**A free, stable and efficient image management tool based on GitHub API. **

---

**Soul torture, have you ever worried about bed problems? ❓**

> I’m writing an article on a static blog website, and I’m worried about how to save the pictures. It’s annoying~

> The link to your favorite picture copied from the Internet becomes invalid one day after using it, annoying~

> Spending money to rent a cloud server to host images is not worth it, and the uploading operation is very cumbersome and annoying~

> I have used a certain company’s free picture bed, but it has a time limit, is slow, has small storage space, and has limited traffic, which is annoying~

**Isn’t there a truly free, stable, unlimited, and fast access image management tool? ┭┮﹏┭┮**

<h2>Yes! </h2>

**PicX, a picture bed management tool based on GitHub API, is free, stable, fast, and efficient. It requires no downloading and installation. You can use it by opening the [PicX website](https://picx.xpoet.cn/). **

You only need to register a GitHub account and create a warehouse to serve as your image bed. Of course, I believe you already have a GitHub account.

## Features Features

- [x] **Drag and drop images** to upload.

- [x] **Copy and paste image** to upload.

- [x] **Select folder images** to upload.

- [x] Image **rename**.

- [x] Picture name **hash** (to ensure that the picture name will never be repeated).

- [x] Copy GitHub and CDN image external links with one click.

- [x] Automatic directory (can automatically generate a directory for storing pictures).

- [x] Picture bed management (add, delete, modify and check warehouse pictures).

- [ ] Image Compression.

- [ ] Bulk upload.

- [ ] Access Gitee & coding repository.

- [ ] Language internationalization.

## How to use How to use

1. Create a [GitHub repository](https://github.com/new) to store images.

   ![](https://cdn.jsdelivr.net/gh/XPoet/image-hosting@master/PicX/image.j1486dtk68n.png)

 <br>

2. Create a [GitHub Token](https://github.com/settings/tokens/new) with repo permissions.

   ![](https://cdn.jsdelivr.net/gh/XPoet/image-hosting@master/PicX/image.lpt1xl9fu.png)

   The newly generated Token will only be displayed once. If it is lost, just regenerate it.

   ![](https://cdn.jsdelivr.net/gh/XPoet/xpoet-image-hosting/PicX/image.krns6rvn9l.png)

<br>

3. Enter [PicX official website](https://picx.xpoet.cn/) to configure the image bed (bind GitHub Token, warehouse and directory to store images).

   1. Fill in the Token and automatically obtain the warehouse under the user.

      ![](https://cdn.jsdelivr.net/gh/XPoet/image-hosting@master/PicX/17961602582378_.pic.7955twzzcmc0.jpg)

   2. In the warehouse drop-down list, select a warehouse as the image bed.

      ![](https://cdn.jsdelivr.net/gh/XPoet/image-hosting@master/PicX/17971602582459_.pic.236arf47qso0.jpg)

   3. Select a directory method (the directory is the folder in the warehouse where pictures are stored).

      ![](https://cdn.jsdelivr.net/gh/XPoet/image-hosting@master/PicX/dirModel.2mnglli43fk0.jpg)

      - Create a new directory: You need to manually enter a new directory.

      - Root directory: Images will be stored directly in the root directory of the warehouse.

      - Automatic catalog: Automatically generate a catalog with date format `YYYYMMDD`. For example: `20200909`.

      - Select warehouse directory: automatically obtain all directories under the warehouse, just select one.

      After completing the configuration of the picture bed, you can now start uploading pictures. Go and try it~

<br>

4. Upload pictures.

   - You can upload images by **drag-and-drop** to the upload area.

   - You can upload by **copying and pasting images** into the upload area. When pasting a picture, you need to click to activate the upload area first, as shown in the figure below. **The dotted border of the upload area turns dark blue, indicating that it has been activated**. Supports pasting via keyboard shortcuts (`ctrl + v` / `command + v`).

     ![](https://cdn.jsdelivr.net/gh/XPoet/image-hosting@master/PicX/image.6wfw84e4xlw0.png)

   - You can upload through **Select Picture** to the upload area.

    After selecting the image, the detailed information of the image will be displayed. You can **customize the name of the image** and **add a hash to the image (make sure the image name is not repeated). **

    ![](https://cdn.jsdelivr.net/gh/XPoet/image-hosting@master/PicX/image.3ibdn25rjfe0.png)

<br>

5. After the image is uploaded successfully, you can copy the image external link.
   ![](https://cdn.jsdelivr.net/gh/XPoet/image-hosting@master/PicX/18031602583963_.pic_hd.70kvd1kgb880.jpg)

<br>

6. Picture bed management, managing the pictures saved in the warehouse.
   ![](https://cdn.jsdelivr.net/gh/XPoet/image-hosting@master/PicX/ihm.3nr0yt9vrtk0.png)

## Contribution

All forms of contributions are welcome, including but not limited to: beautifying the interface, adding functions, improving code, fixing bugs, etc.

## Feedback

If you encounter any problems during use, please submit an `Issue` to the author.

## License

[MIT](https://github.com/XPoet/picx/blob/master/LICENSE) Copyright (c) 2020 XPoet
