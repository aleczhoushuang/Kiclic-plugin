
<a id="readme-top"></a>


<br />
<div align="center">
  <a href="https://github.com/aleczhoushuang/Kiclic-plugin">
    <img src="https://kiclic.com/docs/KiclicLogo.png" alt="Logo" width="250" height="80">
  </a>

  <h3 align="center">Kiclic plugins</h3>

  <p align="center">
    Instructions to add Kiclic plugins on webpages
    <br />
    <a href="https://kiclic.com"><strong>Visit the app website for more informations on the app</strong></a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About Kiclic plugins</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#integration-on-html-page"></a>Integration on HTML page</li>
        <li><a href="#integration-on-content-management-system(cms)">Integration on Content Management System (CMS)</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a>
      <ul>
        <li><a href="#vertical-plugin"></a>Vertical plugin</li>
        <li><a href="#horizontal-plugin">Horizontal plugin</a></li>
        <li><a href="#parameters">Parameters</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This tutorial will help you install the new plugins of Kiclic on your personal webpage using HTML code. 

Please note that no prerequisite or installations are needed to integrate these plugins on your webpage.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

There will be four different plugins that you can integrate on your webpage. In this section, we will first show you how to add the HTML code in your webpage.

### Integration on HTML page

In your html code, you will need to call an iframe and replace "{uuid}" with your user uuid from the Kiclic application:

```sh
<iframe 
  src="https://kiclic.com/plugin/shotgun_plugin_vertical.html?uuid={uuid}" 
  style="width: 300px; height: 540px;" 
  frameborder="0">
</iframe>
```

### Integration on Content Management System (CMS)

In this section, we will take the example of the Wordpress CMS.

When editing your page, you can add an HTML element (Personalized HTML on Wordpress) and you will need to add the following code inside of it:

```sh
<iframe 
  src="https://kiclic.com/plugin/shotgun_plugin_vertical.html?uuid={uuid}" 
  style="width: 300px; height: 540px;" 
  frameborder="0">
</iframe>
```

If you visualize nothing after changes, you can replace the above code with this one:

```sh
<div style="position: relative; overflow: hidden; width: 300px; margin: 0 auto;">
  <iframe 
    src="https://kiclic.com/plugin/shotgun_plugin_vertical.html?uuid={uuid}" 
    style="width: 300px; height: 540px;" 
    frameborder="0">
  </iframe>
</div>
```

The width of your div element shall match the width of your iframe for a centered iframe.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

In this section, we will show you all the parameters you can use to change your plugin structure.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Vertical plugin

* To have a vertical plugin, you will need to change the src code like:
  ```sh
  <iframe 
    src="https://kiclic.com/plugin/shotgun_plugin_vertical.html?uuid={uuid}" 
    style="width: 300px; height: 540px" 
    frameborder="0">
  </iframe>
  ```
  <img src="https://kiclic.com/docs/plugin-vertical.png" alt="Logo" width="300" height="540">

* To have a thin vertical plugin, you will need to change the src code with:
  ```sh
  <iframe 
    src="https://kiclic.com/plugin/shotgun_plugin_thin_vertical.html?uuid={uuid}" 
    style="width: 150px; height: 495px;"
    frameborder="0">
  </iframe>
  ```

  <img src="https://kiclic.com/docs/plugin-thin-vertical.png" alt="Logo" width="150" height="495">

### Horizontal plugin

* To have a horizontal plugin, you will need to change the src code like:
  ```sh
  <iframe 
    src="https://kiclic.com/plugin/shotgun_plugin_horizontal.html?uuid={uuid}" 
    style="width: 450px; height: 260px;" 
    frameborder="0">
  </iframe>
  ```

  <img src="https://kiclic.com/docs/plugin-horizontal.png" alt="Logo" width="450" height="260">

* To have a thin horizontal plugin, you will need to change the src code with:
  ```sh
  <iframe 
    src="https://kiclic.com/plugin/shotgun_plugin_thin_horizontal.html?uuid={uuid}" 
    style="width: 450px; height: 135px;"
    frameborder="0">
  </iframe>
  ```

  <img src="https://kiclic.com/docs/plugin-thin-horizontal.png" alt="Logo" width="450" height="135">

### Parameters

You will be able to set the width and the length of your plugin as well as other parameters like:

| Parameter       | Example      | Style    |
| --------------- | ------------ | -------- |
| titleColor      | black        | Color    |
| textColor       | gray         | Color    |
| timerColor      | white        | Color    |
| timerBackColor  | violet       | Color    |
| timerHoursColor | black        | Color    |
| backgroundColor | white        | Color    |


* You will call these parameters as below in your HTML code:
  ```sh
    <iframe
    src="https://kiclic.com/plugin/shotgun_plugin_horizontal.html?uuid=5f5a833f-183e-11ee-a497-fa163eed83e6&titleColor=black&textColor=gray&timerColor=white&timerBackColor=violet&timerHoursColor=black&backgroundColor=white"
    style="width: 450px; height: 260px;" frameborder="0"></iframe>
  ```

<!-- CONTACT -->
## Contact

Kiclic Instagram - [https://www.instagram.com/kiclic_profite]https://www.instagram.com/kiclic_profite

Kiclic Facebook: [https://www.facebook.com/profile.php?id=61559798553597](https://www.facebook.com/profile.php?id=61559798553597)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
