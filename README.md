# VLPlayerSDKDoc

Steps to import aar file 

Step 1 - Create new Module

<img width="851" alt="Screenshot 2024-11-25 at 10 42 11 PM" src="https://github.com/user-attachments/assets/0e50a7a0-36b1-4e94-a176-216eadc1f866">

Step 2 - replace build.gradle file content with below data

`
configurations.maybeCreate("default")
artifacts.add("default", file("vlplayer-2.4.6.aar"))
`

Step 3 - Sync the project with new Module 

`
implementation(project(":vlplayer"))
`


