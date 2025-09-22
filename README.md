# Содержимое репозитория

1. dataset_1937770_3.txt - исходный датасет: id,text
2. freqrnc2011.csv - сырые частоты словоформ
3. preparation.ipynb - подготовка словаря: частоты -> p -> cost; сохранение CSV - word_forms_with_cost.csv (готовый словарь {word_form, cost}) - из-за большого размера не загружен, но он полностью воспроизводится preparation.ipynb
4. main.ipynb - основной блок: обработка исходного файла + алгоритм восстановления пробелов + сборка финального файла
5. submission.csv - итоговый файл с колонками: id,predicted_positions
6. submissionfull.csv - расширенный файл с колонками: id,text,predicted_positions

# Как запустить?

0. Скачать файлы 1-4 в одну папку
1. Открыть preparation.ipynb и запустить все ячейки
2. Открыть main.ipynb и запустить все ячейки
