1. Kiedy Git wykona fast-forward, a kiedy powstaje merge commit?
	> fast-forward zostanie wykonany, jeśli istnieje oczywista metoda połączenia zmian z mergowanych gałęzi
2. Czym w praktyce różni się merge od rebase?
	> merge łączy dwie gałęzie w jednym punkcie, albo fast-forwardując, albo poprzez merge commit; rebase nadpisuje historię jednej z nich odtwarzając zmiany na niej dokonane ponad zmianami z drugiej gałęzi
3. W jaki sposób został rozwiązany konflikt w Twoim repozytorium?
	> w zasadzie zależy, w gałęzi `t-textreplace` dokonałem zmiany poprzez merge, później w gałęzi `feature-average-rebase` po dokonaniu zmian zrobiony został rebase (wymagający merge'a) na main, na samym końcu merge z `feature-average-rebase` do `main`
