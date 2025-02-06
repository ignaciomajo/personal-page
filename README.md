# Proyecto - Página Personal

![README-personal-page](https://github.com/user-attachments/assets/d5f88205-c4d8-4415-8ba8-da8bf0f30e91)

## Index. :clipboard:

1. Project Description.
2. Project Access.
3. Features and Applications Demonstration.
4. Techniques and Technologies Used.
5. Project Collaborators.
6. Project Developer.

## 1. Project Description. :books:

This project consists of developing a personal webpage with a modern, harmonious, and fully responsive design, ensuring an optimal user experience on mobile devices, 
tablets, and desktop computers.<br>

The site structure has been conceived as a flexible and customizable prototype, allowing users to easily modify the information and links to their social networks. 
Its purpose is to serve as a digital business card, ideal for professionals, freelancers, or anyone who wishes to share their profile in an elegant and accessible manner.<br>

With an intuitive interface and carefully selected aesthetics, this webpage provides an efficient platform to highlight the user's digital identity, 
facilitating connections with potential contacts, clients, or collaborators.<br>

I have decided to write both the project and this file in English to reach a broader community.<br>

You can access the project deployment at this link to see how it looks on the device of your choice: https://ignaciomajo-personal-page.vercel.app/

## 2. Project Access. :open_file_folder:

You can access the project in two simple ways:

**Option 1:** Clone using Git

From your command line, select the directory where you want to download the project and run the following command:

`git clone https://github.com/ignaciomajo/personal-page`

This command will create a copy of all the necessary files to use the project.

**Option 2:** Download ZIP

If you do not want to use the command line, go to the project URL: https://github.com/ignaciomajo/personal-page

In the top right corner, you will see the `<> Code` section. Click on it, and you will see the `Download ZIP` option.

Then, navigate to the directory where you cloned or downloaded the zip file, and you should have the following files:

![respository-download-image](https://github.com/user-attachments/assets/46100d35-e72c-4a34-a292-951cbc58fffa)

After completing these steps, you can access the files using a text editor such as Visual Studio Code to modify the template and develop your personal project.

## 3. Features and Applications Demonstration. :memo:

### Features Demonstration.

When you open the `index.html file`, your browser will take you to the following screen:

![home-page](https://github.com/user-attachments/assets/fdcf2188-daeb-4384-bf96-22a0d9947f89)

The following image shows the different functionalities of the main screen:

![project-presentation](https://github.com/user-attachments/assets/ae8f0fcd-b2e2-41e5-ab4f-015eb089438c)

Clicking on the `About Me` link will redirect you to the following page:

![about-me-page](https://github.com/user-attachments/assets/c1d311e6-6d9d-4349-8c39-cbff5a2a3e13)

Clicking on `Curriculum Vitae` will take you to:

![image](https://github.com/user-attachments/assets/2cf5f76d-b8bd-4d1b-8405-5600eae6357b)

*Note*: Your picture here will be aligned with your work experience length.

### Applications

As previously mentioned, this project is a template for developing your personal webpage.

Below, I will detail some steps to complete your information and use this template as your own project.

#### - :arrow_down: PREREQUISITES:

For the demonstration of these steps, I will use Visual Studio Code.

If you have not installed it yet, you can download it from: https://code.visualstudio.com/download

Or, if you prefer, you can use any text editor you are familiar with.

**"HOME" PAGE CONTENT:**

![index-html](https://github.com/user-attachments/assets/f72b8fd5-ae51-4294-90c4-85285a82be8d)

As seen on the left of the image, each line of code has a reference number. I will use this to indicate the modifications to be made:

**- Line 6:**

`<title> </title>` Here you can see the text: "Ignacio Majo's Portfolio - Home." This text is the page title, which appears in the browser tab.

You can modify it to display your name (only change the text).

Example:

`<title>(Your Name)'s Portfolio - Home</title>`

**- Lines 19 to 22:**

Everything between `<h1> </h1>` is the main header of your page. Inside, whatever is enclosed in `<strong> </strong>` will change color.

Modify only the text as shown previously.

Example:

`<h1 class="presentacion__contenido__titulo">
This will be the title of <strong class="strong__h1"> My Portfolio </strong>`

**- Lines 23 to 28:**

Everything between <p> </p> is the brief description of the homepage.
Modify only the text as previously indicated.

**- Lines 29 to 37:**

This section corresponds to links to your social networks.

Each link is enclosed in `<a> </a>`.

* The `href="URL"` property should contain the URL of the social network you want users to visit when clicking the link.

* The `src=./assets/image-name.png` property refers to the logo of the social network you are linking to. Inside the assets folder, you will find some useful icons.

* Before `</a>`, enter the name of the corresponding social network.

*Note:*

You can add more links or remove some if needed.

* To add more links, copy an entire <a> </a> block and paste it below the last one of this style. Modify the properties mentioned above.

* To remove a link, simply delete an entire `<a> </a>` block.

**- Line 39 to 41:**

This line corresponds to the image that you want to appear on your website. To do this, add the image to the assets:file_folder: folder, and then:

* Modify the `src="./assets/Image.png"` property as follows: `src=".assets/image-name.extension`

* The `alt=" "` property is important for accessibility. Develop a brief description of the selected image.

**- Line 44:**

Here you can modify the text with your name to denote you have been the one who developed your website. You can also add any kind of information you wish to.<br>





