dev/tty 

命令行 [ctrl]+[Alt]+[F1]~[F6] 切换
图形   [ctrl]+[Alt]+[F7] 切换

#创建文件 file
$ touch file 

#进入 etc目录
$ cd /etc/

#查看当前目录
$ pwd


shiyanlou:~/ $ echo 'shiyanlou'                                      [12:07:36]
shiyanlou


#快捷键  
1.[Tab] 命令补全 目录  命令参数
2.[Ctrl+c] 强行终止当前程序

$find / 

$ cd /home/shiyanlou                                    [12:12:46]
$ touch asd.txt fgh.txt                                 [12:16:48]
$ ls *.txt                                            
asd.txt  fgh.txt


需要一次性创建多个文件 

$ touch love_{1..10}_shiyanlou.txt                     
$ ls *.txt                                              
asd.txt                love_2_shiyanlou.txt  love_6_shiyanlou.txt
fgh.txt                love_3_shiyanlou.txt  love_7_shiyanlou.txt
love_10_shiyanlou.txt  love_4_shiyanlou.txt  love_8_shiyanlou.txt
love_1_shiyanlou.txt   love_5_shiyanlou.txt  love_9_shiyanlou.txt

$ man  Manual pages  帮助
$man man

man [1..8] ls

$man 1 ls


$ls --help 
$sudo apt-get update
$sudo apt-get install sysvbanner
$banner Liunx
shiyanlou:~/ $ banner Linux                                          [12:06:51]
#
#           #    #    #  #    #  #    #
#           #    ##   #  #    #   #  #
#           #    # #  #  #    #    ##
#           #    #  # #  #    #    ##
#           #    #   ##  #    #   #  #
#######     #    #    #   ####   #    #

shiyanlou:~/ $ printerbanner -w 50 A                                  [12:33:58]
            # 
            # 
            ###
            ######
            #    #####
                      #### 
                      ## #### 
                      ##     #####
                      ##         ##### 
                      ##            #####
                      ##          ############
                      ##      ##############
                      ##   ##############
                      ############## 
            #      ###############
            #  ###############
            #############
            ##########
            ######
            ##
            # 



$toilet ,figlet   
$ toilet Linux                                          
                                   
 m        "                        
 #      mmm    m mm   m   m  m   m 
 #        #    #"  #  #   #   #m#  
 #        #    #   #  #   #   m#m  
 #mmmmm mm#mm  #   #  "mm"#  m" "m 
                                   
                                   
$ figlet Linux                                         
                                   
 m        "                        
 #      mmm    m mm   m   m  m   m 
 #        #    #"  #  #   #   #m#  
 #        #    #   #  #   #   m#m  
 #mmmmm mm#mm  #   #  "mm"#  m" "m 
                                   




