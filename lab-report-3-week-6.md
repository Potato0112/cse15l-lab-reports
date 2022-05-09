# Lab Report 3 - Week 6
## Streamlining ssh Configureation

Because typing the entire ssh name can be hard to remember, a good way to streamline the process is to simplify the name. This can be done through the configuration file located at `~/.ssh/config`. <br>
The first step is to install the VS code SSH extension. It should appear as a new icon on the left side of the window. <br>
![Image](lab3images/ssh-homepage(1).png) <br>
Select the SSH Target. In this case, it's the ieng6 server. <br>
![Image](lab3images/ssh-target(2).png) <br>
Click the gear icon. <br>
![Image](lab3images/gear-icon(3).png) <br>
Go to the search bar and from the drop down, select the option that ends with `~/.ssh/config`. <br>
![Image](lab3images/select-config-path(4).png) <br>
Edit the `config` file by changing the `Host` name to something shorter like `ieng6`. As you can see, after changing the `Host` name, it's possible to use the new name to ssh into the server using `ssh ieng6`. <br>
![Image](lab3images/simple-login(5).png) <br>
It is also possible to use the new simplified name to move files from 
