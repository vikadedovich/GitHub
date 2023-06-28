### GitHub HW_2

1. На локальном репозитории сделать ветки для:
   - Postman: 

     `git branch Postman`
     
   - Jmeter: 

     `git branch Jmeter`
     
   - CheckLists: 

     `git branch CheckLists`
     
   - Bag Reports: 

     `git branch Bug_Reports`
     
   - SQL:

     `git branch SQL`
     
   - Charles: 

     `git branch Charles`
     
   - Mobile testing: 

     `git branch Mobile_testing`
     
3. Запушить все ветки на внешний репозиторий:

   `git push --all`
   
5. В ветке Bag Reports сделать текстовый документ со структурой багрепорта:

   `git checkout Bug_Reports && cat > bug_report.txt`
   
7. Запушить структуру багрепорта на внешний репозиторий:

   `git commit -a "create bug_report.txt" && git push --set-upstream origin Bug_Reports`
   
9. Вмержить ветку Bag Reports в Main:

   `git checkout main && git merge Bug_Reports`
   
11. Запушить main на внешний репозиторий:

    `git push`
   
13. В ветке CheckLists набросать структуру чек листа:

    `git checkout Checklist && cat > checklist.txt`
   
15. Запушить структуру на внешний репозиторий:

    `git commit -a "add checklist.txt" && git push --set-upstream origin CheckLists`
   
16. На внешнем репозитории сделать Pull Request ветки CheckLists в main:

    `Merge pull request=>confirm merge`
   
18. Синхронизировать Внешнюю и Локальную ветки Main:

    `git pull`
