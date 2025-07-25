### DbVisualizer License (Ubuntu)

#### [Source repo](https://github.com/xiaguliuxiang/dbvisualizer-agent)

#### 1. Download and install DbVisualizer for your system from the [official website](https://www.dbvis.com/download/) (tested on `v24.3.4`)

#### 2. Download `dbvisualizer-agent.jar` from the [release page](https://github.com/Gasprinskiy/dbv-licence/releases)

#### 3. Place `dbvisualizer-agent.jar` in `/home/username/.dbvis` or another preferred location

#### 4. Locate the `DbVisualizer` folder containing the `dbvis.vmoptions` file (typically in `/opt/DbVisualizer`)

#### 5. Add the following line to `dbvis.vmoptions`:
```
-javaagent:/path/to/dbvisualizer-agent.jar
```
Replace `/path/to/` with the actual path where you placed `dbvisualizer-agent.jar`.

#### 6. Run the following command to generate a key and copy it:
```
java -jar /path/to/dbvisualizer-agent.jar
```
Replace `/path/to/` with the actual path to `dbvisualizer-agent.jar`.

#### 7. Create a `dbvis.license` file in the `/home/username/.dbvis` directory and paste the key generated in the previous step

#### 8. Run DbVisualizer and enjoy

#### Important note: This tool is intended for personal use only. For commercial use, please purchase a DbVisualizer license.

