# Installing Development Tools

Tizen SCM tools support the following Linux distribution versions:

- Ubuntu 20.04/18.04/16.04/14.04
- openSUSE 13.2/Leap 42.1/42.3

> **Note**
>
> These tools are maintained in http://download.tizen.org/tools/latest-release/ .
> If you cannot find your linux system, that means currently tizen SCM tools doesn't support your OS system.
> But if you want to use tools although your OS system,
> you can find http://download.tizen.org/tools/archive/, Tizen SCM tools are stored that repository.

You can install a variety of development tools, including:

- **Git Build System (GBS)** command line tool that supports Tizen package building.
- **Image Creator (MIC)** command line tool that supports Tizen image creation.

> **Note**
>
> GBS and MIC are used as examples because they are mandatory development tools for Tizen developers.

## Installing Development Tools in Ubuntu or Debian

To install a development tool in Ubuntu or Debian:

> **Note**
>
> The `apt-get install <Package_Name>` command is recommended because it upgrades 1 or more already installed packages without upgrading every package installed, whereas the `apt-get upgrade` command installs the newest version of all currently installed packages. In addition, `apt-get update` must always be executed before `apt-get install <Package_Name>` or `apt-get upgrade`, to resynchronize the package index files.

1. Use the following command to set up the Tizen repository in your apt list.

   ```
   echo "deb [trusted=yes] http://download.tizen.org/tools/latest-release/Ubuntu_$(lsb_release -rs)/ /" | \
   sudo tee /etc/apt/sources.list.d/tizen.list > /dev/null
   ```
   > **Note**
   >
   > The `lsb_release -rs` sub-command below returns the version of your Ubuntu distribution.


   > **Note**
   >
   > You can set up the Tizen repository manually like below:
   > 1. Open the package manager source list using a text editor.
   >
   >    VIM is used in the following example:
   >
   >    ```
   >    $ sudo vim /etc/apt/sources.list.d/tizen.list
   >    ```
   >
   > 2. Add the Tizen tools repository to the source list.
   >
   >    ```
   >    deb [trusted=yes] http://download.tizen.org/tools/latest-release/Ubuntu_<version>/ /
   >    ```
   >
   >    For example:
   >
   >    - In Ubuntu 20.04, append the following line to the source list:
   >
   >      ```
   >      deb [trusted=yes] http://download.tizen.org/tools/latest-release/Ubuntu_20.04/ /
   >      ```
   >
   > Pay special attention to the space between the URL and "/".

2. Resynchronize the package index files from the sources specified in the source list and install development tools:

   ```
   sudo apt-get update && sudo apt-get install gbs mic
   ```

## Installing Development Tools in openSUSE

To install a development tool in openSUSE:

1. Add the Tizen tools repository to the package manager source list.

   In openSUSE 13.2, for example:

   ```
   $ sudo zypper addrepo http://download.tizen.org/tools/latest-release/openSUSE_13.2/ tools
   ```

   > **Note**
   >
   > Pay special attention to the space between the URL and "tools".

2. Install a development tool:

   ```
   $ sudo zypper refresh
   $ sudo zypper install gbs mic
   ```
