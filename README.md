1. What is the difference between GIT and SVN?
Mueyyen qeder oxwardir.Git daha yaxwidi. Meslen merge ve branching daha suretli
sekilde yerine yetirilir. Internet baglantisi olmasa bele kodlari commit ede bilirik.
2. What are the advantages of using GIT?
Team work, pull requestler suretlidir.
3. What is “Staging Area” or “Index” in GIT?
Gitin diqqet ceken birterefi indexdir ki, copy de her hansi bir fayl deyisdirdik , bu fayl git add
ile indexe yuklenir ve muveqqeti orda olur. Staggin areada proses bele gedir:
4. What is GIT stash?
Git stasdan istifasde etmek odur ki, deyiwikleri mueyyen vaxta yadda saxlayir.bu esas
yarim saxladigimiz laiyelerde istifade olunur.
5. How will you know in GIT if a branch has been already merged into master?
git branch --merged master - mastere merg olanlarin siyahisi git branch --merged - HEAD
merg olanlarin siyahisi git branch --no-merged - merge olmayan branchlarin siyahisi
6. What is the function of git clone?
Reponu yeni yaranmiw direktoriyaya clone etmek ucun istifade olunur. Clone edilmis
repoda butun silinmis budaqlanmalarinin izlemelerini yaradir.
7. What is the function of ‘git config’?
Global ayarlari get ve ya set elmek ucun istifade olunur. Misal user name ve ya passw
deyiwdikde istifade olunur.
8 . What is ‘head’ in git and how many heads can be created in a repository?
Biz bunu adsiz temporary barnch kimk tesvvur ede bilerik.Bu sizin commitleriniz qebul edir.
9. What is the purpose of branching in GIT?
Serbest sahedir ki edit commit prosesler ucun abstarkt xidemetler yaradir.
10. How can you bring a new feature in the main branch?
$git branch [branch_adi] bu mastere oturulmur onu safe saxliyir lazim geldikde mastere
oturule biler.
11. How can conflict in git resolved?
Her hansi istifadeci eyni bir kodda ve ya setrde deyiwikik edirse onda conflict yaranacaq.
Bu deyiwiklerden biri silinir bir qalmalidir.
12. To delete a branch what is the command that is used? To delete a branch what is the
command that is used?
$git branch -d $git branch -rd
13. What is another option for merging in git?
Merging asand ve integrasiya olunmuw deyiwklikleri edir ,bunun helli bawqa yolla da
ola biler: rebase merge in alternativ ola biler
14. What is the syntax for “Rebasing” in Git?
$ git rebase master
15. What is the difference between ‘git remote’ and ‘git clone’?
Remote baglanti yaradir ancaq sen bunu secdiyin arasinda elaqe qura bilersen, clone ise
istenilen repodan clone ede biler.
16. What is the function of ‘git diff ’ in git?
Faylin İndiki halla evvelki hal arasinda ferq demekdir
17. What is the function of ‘git checkout’ in git?
İwledilen treedeki update olunmuw fayllar index ve ya mueyyen treeye matc olunur.Eger
muyen yollar verilmese git checkout teyin olunmuw branchi al azirdaki branc kimi update
edir.
$ git checkout -b <branch> --track <remote>/<branch> sytax beledir.
18. What is the function of ‘git reset’?
Fayllar uzerideki deyiwikleri geri qaytarmaq ucundur.
git reset –soft 1 addim geri qaytarir
git reset –hard butun deyikleri geri qaytarir.
18. What is the function of ‘git reset’?
Fayllar uzerideki deyiwikleri geri qaytarmaq ucundur.
git reset –soft 1 addim geri qaytarir
git reset –hard butun deyikleri geri qaytarir.
