# oneDrone-Tracker

### Downloads
```shell
git clone --recurse-submodules https://github.com/dnjstjr93/oneDrone-Tracker.git
```

### Settings
1. Crow-B

    in CMD on Windows
    ```shell
    > scp -r nCube-Man-CrowB nCube-Man-CC nCube-RC-CC nCube-TELE-CC nCube-RC-HUB-CrowB nCube-TELE-HUB-CrowB pi@192.168.101.100:/home/pi
    ```
2. Crow-Cube

   in Terminal on Crow-B
    ```shell
    > scp -r *-CC pi@192.168.50.36:/home/pi
    ```
   
### Install & Run
1. Crow-B

   - nCube-Man-CrowB
      ```shell
      cd nCube-Man-CrowB && npm install && npm start
      ```
   - nCube-RC-HUB-CrowB
      ```shell
      cd nCube-RC-HUB-CrowB && npm install && npm start
      ```
   - nCube-TELE-HUB-CrowB
      ```shell
      cd nCube-TELE-HUB-CrowB && npm install && npm start
      ```
2. Crow-Cube

   - nCube-Man-CC
      ```shell
      cd nCube-Man-CC && npm install && npm start
      ```
   - nCube-RC-CC
      ```shell
      cd nCube-RC-CC && npm install && npm start
      ```
   - nCube-TELE-CC
      ```shell
      cd nCube-TELE-CC && npm install && npm start
      ```

   ##### ※ check pm2 list or pm2 logs
