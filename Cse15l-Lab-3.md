## Lab report - 3  
## Researching Commands  
So for this task I will choose less.And I will run some command to show you when and for what reason do we need to use it.  

![01](https://user-images.githubusercontent.com/122565144/221750134-7fe506a3-605b-4039-bd3b-da6e95506b10.jpg)  
![0](https://user-images.githubusercontent.com/122565144/221750257-d6dac5fb-0bff-4931-8606-c5cebb4e3c25.jpg)  
![00](https://user-images.githubusercontent.com/122565144/221750286-61c3035c-7122-4964-883c-0f325e7b5e3e.jpg)  
![000](https://user-images.githubusercontent.com/122565144/221750312-3b7743ad-5458-4db3-9c86-1bd1b192234e.jpg)  

## Option: -N (display line numbers)  
This option displays line numbers next to the lines of the file being viewed in less. This can be useful if you want to reference specific lines of the file.So I will do this task for difreent files so we can see the lines diffrence.  


Examples 1:  

![Post 222](https://user-images.githubusercontent.com/122565144/221747559-785ce49b-b1a0-4879-979d-01e0ac6c516b.jpg)  
![Post 22](https://user-images.githubusercontent.com/122565144/221747613-43841e10-1413-4aa3-af45-7ae8ee501bdf.jpg)  

Examples 2:-  
And if we try this on a different file the task is the same but it has diffrent out put.  

![-N sec 1](https://user-images.githubusercontent.com/122565144/221751572-f0bae34d-361d-48f3-aeee-72b584613f15.jpg) 
![-N second](https://user-images.githubusercontent.com/122565144/221751526-069e8cd3-6e50-4472-9021-d0cb0dd2236a.jpg)  

In this example, less displays the contents of Algarve-WhereToGo.txt with line numbers on the left-hand side of the terminal screen. The -N option is used to enable the display of line numbers.  


## Option: -s (squeeze multiple blank lines into one)  
This option removes extra blank lines in the file being viewed in less. This can be useful if the file has extra blank lines that you don't need to see.  

Examples:  

![-s 0](https://user-images.githubusercontent.com/122565144/221748694-cfdeeb6e-cce2-43eb-b9eb-3a717e043443.jpg)  

![-s 1](https://user-images.githubusercontent.com/122565144/221748819-bb3b75bb-4a83-43b0-90a5-264736f3c0f1.jpg)  

## You can use the less command in combination with the grep command to find a specific word in a file.  
So for this example i try to search my name which is ARON and it print the sentence which it has Baron which is my full name on it. So I will try this in different files with two examples.  
## Example 1:-  

![grep name 1](https://user-images.githubusercontent.com/122565144/221754037-a3888413-5adc-41d7-9a90-8d7a4c0a423f.jpg) 

## Example 2:-  
Now I try to find Lucayans in the folder and I fond it as you see below.  


![grep name 2](https://user-images.githubusercontent.com/122565144/221754094-09134f29-2aa6-47e3-b07f-17e0a7d98f27.jpg)  

In this example, we're using the less command to display the contents of Algarve-WhereToGo.txt on the terminal screen. The | character is used to pipe the output of less to the grep command, which searches for the word "Aron" within the file. The output of the grep command is displayed on the terminal screen, showing only the lines that contain the word "Aron and Lucayanas".

You can replace "Aron" with any other word or regular expression that you want to search for within the file. Note that this method only displays the lines that contain the search term - it doesn't display the entire file. If you want to display the entire file with the search term highlighted, you can use the -i option with less:

## Option: -F

The -F option in the less command is used to automatically exit less if the entire file can be displayed on one screen. This can be useful if you're working with small files and don't want to have to manually exit less after viewing the contents.  


Here's an example of how to use the -F option with less:  
![-f 1](https://user-images.githubusercontent.com/122565144/221760687-27f8853f-25af-4ed2-a272-0ef45e4af861.jpg)  
![-F 2](https://user-images.githubusercontent.com/122565144/221760741-b43289ca-1532-443f-abf9-cd1e3bd2780c.jpg)  

In this example, we're running the less command on the HistoryMadrid.txt file, with the -F option. This will cause less to exit automatically if the entire file can be displayed on one screen.  

When you open the file with less, if the contents of the file can fit on one screen, less will display the contents and immediately exit. If the contents of the file are too long to fit on one screen, less will display the first screen of content and enter the usual paging mode.But as we see our file is larg so it doesn't exit immediately.    

Note that the -F option is generally only useful for small files that can be displayed on one screen. If you're working with larger files, you may still want to use less in the usual paging mode, even if the entire file can technically fit on one screen.  











