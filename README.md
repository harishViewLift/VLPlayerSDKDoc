# VLPlayerSDKDoc

Steps to import aar file 

Step 1 - Create new Module

<img width="851" alt="Screenshot 2024-11-25 at 10 42 11 PM" src="https://github.com/user-attachments/assets/0e50a7a0-36b1-4e94-a176-216eadc1f866">

Step 2 - replace build.gradle of new Module file content with below data

`
configurations.maybeCreate("default")
artifacts.add("default", file("vlplayer-2.4.6.aar"))

<img width="567" alt="Screenshot 2024-11-26 at 8 21 37 AM" src="https://github.com/user-attachments/assets/a216b37d-42bf-4487-b745-801c9316b585">

Step 3 - Sync the project with new Module 

`
implementation(project(":vlplayer"))
`

Pass Response to VLPlayer

https://gist.github.com/harishViewLift/4b26f85b854cc736c65c3c0fc8db44e2


