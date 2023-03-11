---
tags:
  - Reference
---

# Media

=== "Images"

    ```
    ![Linux Screenshot](img/screenshots/screenshot-linux.png)
    ```
    ![Linux Screenshot](img/screenshots/screenshot-linux.png)

    ``` 
    # Modern browsers provide native support for lazy-loading images through the loading=lazy directive, which degrades to eager-loading in browsers without support   
    ![Image title](https://dummyimage.com/600x400/){ loading=lazy }
    ```
    ![Image title](https://dummyimage.com/600x400/){ loading=lazy }

    ```
    <img src="../img/screenshots/screenshot-linux.png" alt="Linux Screenshot" width="400" height="276">
    ```
     <img src="../img/screenshots/screenshot-linux.png" alt="Linux Screenshot" width="400" height="276">
    
    ```
    <figure>
     <img src="../img/screenshots/screenshot-linux.png" alt="Linux Screenshot" width="400" height="276">
      <figcaption>Linux Screenshot</figcaption>
    </figure>
    ```
    
    <figure>
     <img src="../img/screenshots/screenshot-linux.png" alt="Linux Screenshot" width="400" height="276">
      <figcaption>Linux Screenshot</figcaption>
    </figure>
    
    
=== "Videos"
    
    ```
    <video width="320" height="240" controls>
      <source src="../vid/abstract.mp4" type="video/mp4">
    </video>
    ```
    <video width="320" height="240" controls>
      <source src="../vid/abstract.mp4" type="video/mp4">
    </video>
    
    ```
    <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/pBy1zgt0XPc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    ```
    <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/pBy1zgt0XPc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>