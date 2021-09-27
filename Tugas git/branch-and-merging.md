1. What does git clean do?
Answer: untuk menghapus file yang tidak terlacak dan dapat menghapus 
file secara permanen

2. What do the -d and -f flags for git clean do?
Answer: git clean -f dapat kita gunakan untuk menghapus file yang tidak 
terlacak, namun jika kita ingin menghapus direktorynya juga kita bisa 
menggunakan -d

3. What git command creates a branch?
Answer: git checkout -b

4. What is the difference between a fast-forward and recursive merge? 
Answer: fast forwards can only happen if there have not been commits on 
the original branch while the new branch is being worked on

5. What git command changes to another branch? 
Answer: git checkout

6. How do you remove modified or deleted files from the working 
directory?
Answer: git reset

7. What git command deletes a branch?
Answer: git branch -D

8. What does the git diff command do?
Answer: Agar dapat mengetahui conflicts pada file

9. How do you remove files from the staging area?
Answer: git reset HEAD name_of_file or git rm --cached name_of_file

10. How do merge conflicts happen?
Answer: When Git can not determine what file or folder to choose when 
merging since there have been different commits with changes to the 
same file.