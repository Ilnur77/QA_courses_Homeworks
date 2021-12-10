Homework #3
1. На локальном репозитории сделать ветки для: git branch (название ветки)
- Postman
- Jmeter
- CheckLists
- Bug Reports
- SQL
- Charles
- Mobile testing

2. Запушить все ветки на внешний репозиторий - git push -u origin --all
3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта - git checkout Bug_reports ; touch bug_rep_structure.txt ; vim bug_rep_structure.txt
4. Запушить структуру багрепорта на внешний репозиторий - git add br_structure.txt ; git commit -m "create br_structure.txt" ; git push -u origin Bug_reports
5. Вмержить ветку Bug Reports в Main - git checkout main ; git merge Bug_reports
6. Запушить main на внешний репозиторий. - git push
7. В ветке CheckLists набросать структуру чек листа. - git checkout CheckLists ; touch checklist_structure.txt ; vim checklist_structure.txt
8. Запушить структуру на внешний репозиторий - git add . ; it commit -m "create checklist_structure.txt" ; git push
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main - На внешнем репозитории нажать на "Compare and pull request", на отобразившейся странице нажать на "Create pull request"
10. Синхронизировать Внешнюю и Локальную ветки Main - git pull
