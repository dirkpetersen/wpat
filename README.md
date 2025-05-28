
 please write a modern R script with command line arguments that reviews work patterns of different user types from early riser to night owl based on file system metadata stored in a CSV file please example below implement this with textual visualization only, no plots 

 

 head ~/gh/labdata.csv
inode,parent-inode,directory-depth,"filename","fileExtension",UID,GID,st_size,st_dev,st_blocks,st_nlink,"st_mode",st_atime,st_mtime,st_ctime,pw_fcount,pw_dirsum
7632860260,7622455692,0,"/home/groups/BakerLab/resfinder.fsa","fsa",5976,4756,2983014,59,7440,1,"0100644",1684452712,1684452712,1684452712,-1,0
7612189455,7622455692,0,"/home/groups/BakerLab/README.txt","txt",0,4756,33,59,64,1,"0100664",1684348571,1684348571,1684348571,-1,0
7614835862,7622455692,0,"/home/groups/BakerLab/testfile.txt","txt",5976,4756,0,59,64,1,"0100664",1684356665,1684356665,1684356665,-1,07622455692,0,-1,"/home/groups/BakerLab","",0,4756,663,59,80,20,"0042770",1706054991,1706054991,1706054991,21,3480965
7613682360,7622592286,1,"/home/groups/BakerLab/doomsday/qiime.po8999213","po8999213",5976,4756,0,59,64,1,"0100664",1684454221,1684454221,1684454221,-1,0
7613681774,7622592286,1,"/home/groups/BakerLab/doomsday/qiime.o8999213","o8999213",5976,4756,7193,59,64,1,"0100664",1684453510,1684453510,1684453510,-1,0
7608008202,7622592286,1,"/home/groups/BakerLab/doomsday/otu_able_no_neg.biom","biom",5976,4756,692577,59,2192,1,"0100664",1684454241,1684454241,1684454241,-1,0
7610549385,7622592286,1,"/home/groups/BakerLab/doomsday/qiime.o9011730","o9011730",5976,4756,0,59,64,1,"0100664",1684454241,1684454241,1684454241,-1,0
