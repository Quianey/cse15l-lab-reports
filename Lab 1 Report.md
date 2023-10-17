## cd
![image](https://github.com/Quianey/cse15l-lab-reports/assets/147276821/a786daa6-3444-44da-ab3e-917eb8cd1cc7)


I run cd with no arguments under **user@sahara**. I get nothing because I'm already under this directory. I don't need to switch to **user@sahara** again. This output is not an error. **The working directory is /home.**

I run cd with a path to **cse15l-lab-reports** under **user@sahara**. Then, the working directory change to **user@sahara ~/cse 15L-lab-reports**. This is because I use cd command switch the current working directory from **user@sahara** to **user@sahara ~/cse15l-lab-reports**. The output is not an error. **The working directory is /home/cse15l-lab-reports.**


I run cd with a path to **cse15l-lab-reports/index.md** under **user@sahara ~/cse15-lab-reports**. There is an error. This is because cd is used to switch the current working directroy to the give path, we here is using a file, instead of a directory. So, it returns an error. **The working directory is /home/cse15l-lab-reports.**

## ls

![image](https://github.com/Quianey/cse15l-lab-reports/assets/147276821/3b6a062f-c3f2-431e-b4f3-7e6b0d57149e)
![image](https://github.com/Quianey/cse15l-lab-reports/assets/147276821/3af05a48-5168-4107-9925-2b1b4d7d3f10)

I run ls with no arguments under **user@sahara**. I get *cse15l-lab-reports* and *LabReport1*. This is because I'm using command ls to list the files and folders under the give path, here is **user@sahara**. As in the second picture, I have file **cse15l-lab-reports** and **LabReport1** in **user@sahara**, which is home file. The output is not an error. **The working directory is /home.**

I run ls with a path to **cse15l-lab-reports**. I get *index.md*, *Lab 1 Report.md*, *Markdown.md*, *README.md*. Similarly, ls lists the files under the give path, **/cse 15L-lab-reports**, and I have those four files in **/cse 15L-lab-reports**. So I get that result. The output is not an error. **The working directory is /home.**

I run ls with a path to **cse15l-lab-reports/index.md**. I get the absolute path to **index.md**, here is **cse15l-lab-reports/index.md**, since ls command when used with file as an argument, it will prints the full path of the file. The output is not an error. **The working directory is /home.**

## cat
![image](https://github.com/Quianey/cse15l-lab-reports/assets/147276821/c2a73a4d-0156-4c6b-b3af-0e10e9f0bd1e)

![image](https://github.com/Quianey/cse15l-lab-reports/assets/147276821/53ab877c-33bf-4ae2-9929-17c58315768c)

I run cat with no argument, under **user@sahara**. I get notheing. Because it's waiting for an input from your keyboard. Since I don't type anyting, the terminal is in blank. But it's not an error. **The working directory is /home.**


I run cat with a path to **cse15l-lab-reports**. I got *cat: ces15l-lab-reports: Is a directory*. Since cat is used to print the contents of one or more files given by the paths, cat can't work with a directory as a path. The output is an error. **The working directory is /home.**


I run cat with a path to **cse15l-lab-reports/index.md**. I get *Hello, world!*. As I mentioned before, cat is used to print the contents of the files. I have *Hello, world!* in **index.md**. And cat will print it out. The output is not an error. **The working directory is /home.**

