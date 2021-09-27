1. What is the difference between git reset and git revert. When would 
you use one over the other?
Answer: git reset dapat kita gunakan jika data/file kita belum commited 
tetapi sudah stagged dan perintah ini akan mengembalikan file ke 
kondisi sebelumnya, dan menghapus history commit berikutnya,
sedangkan git revert dapat membatalkan semua perubahan tanpa menghapus 
commit terakhir

2. What is the difference between git merge and git rebase. When would 
you use one over the other?
Answer: git merge dapat kita gunakan juka ingin menggabungkan branch 
utama dengan branch cabang yang telah kita kembangkan,
sedangkan git rebase digunakan jika kita ingin menggabungkan atau 
menggeser commit base, 
rebase menghasilkan riwayat yang lebih rapi tanpa percabangan, dan 
dapat kita gunakan saat bekerja bersama tim.

3. What is the difference between git stash pop and git stash apply. 
When would you use one over the other?
Answer: git stash apply mengembalikan nilai terbaru dan tetep 
mempertahankannya di stash, 
sedangkan git stash pop akan mengembalikan nilai terbaru tetapi akan 
menghapusnya dari stash

4. What kinds of things can you do in interactive mode when rebasing?
Answer: kita dapat mengedit commits, mengedit/mengubah pesan commit, 
bahkan kita bisa menghapus commits.