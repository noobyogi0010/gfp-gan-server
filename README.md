# GFP-GAN Server

This is the web server for GFP-GAN web app which demonstrates the amazing power of GFP-GAN. This repository is inspired by the continuous tweets regarding how great GFP-GAN is at converting low resolution face images to really crisp and high quality face images.

## Demo

![GFP-GAN-App Demo](https://github.com/noobyogi0010/gfp-gan-app/blob/0111/sanity/assets/demo/demo.gif)

## Local Setup

You can run the server in your local system using the following commands:

- Install all the project dependencies using the following command:

    `pip install -r ./requirements.txt`

- Run the following command to start the server:

    `python ./app.py`

## Just FYI...

If you are looking for the front-end implementation, then you can find it here: [**GFP-GAN-App**](https://github.com/noobyogi0010/gfp-gan-app).

## Future Scope

This can be considered as the base version of the server, as I am planning to develop it further with much more enhancements. As of now following are the things that I have forethought to work upon in the upcoming months:

- [x] Deploying the server on `GCP Cloud Run` or similar service.

- [ ] Make the code more modular by breaking obvious implementations into independent components.

- [ ] Improve the code quality by learning more best practices for React and Typescript.

- [ ] Reducing the dependency on the inference created by GFP-GAN creators in their github repo.

## Contributor Guide

Interested in contributing?

It's pretty straight forward and simple. Follow the below steps and you're welcome to the world of open source:

- You came across an **issue** while going through the application, then please follow these steps:

    - Head over to the **Issues** tab and click on `New Issue` button.
    - Enter the title as described below:

        `[Issue] - Short Description For Your Issue`

    - In describe section, mention the following in detail:

        - Steps to reproduce the issue.
        - Expected output.
        - Actual output.
        - Screenshots or screencasts (if any).
        - Environment.

    - Finally click on `Submit New Issue` and you are done!

- You want to raise a **feature request**? It's simple also, follow the below steps:

    - Head over to the **Issues** tab and click on `New Issue` button.
    - Enter the title as described below:

        `[Issue] - Short Description For Your Issue`

    - In describe section, mention the following in detail:

        - Feature description.
        - Motivation for feature (optional).

    - Finally click on `Submit New Issue` and you are done!


## Learn More

You can learn more about **GFP-GAN** from this amazing repo [here](https://github.com/TencentARC/GFPGAN).
