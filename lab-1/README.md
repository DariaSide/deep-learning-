# Лабораторная работа №1

Тема: свёртки, обучение глубоких сетей и adversarial robustness.

## Содержимое

- `hw1.ipynb` — полностью выполненный notebook с сохранёнными результатами;
- `hw1.pdf` — тот же notebook в удобном формате для просмотра;
- `requirements.txt` — зависимости из задания;
- `assignment.txt` — исходные инструкции к работе;
- `artifacts/` — метрики и checkpoint-файлы моделей.

## Результаты

- ResNet-20 на CIFAR-10: test accuracy `0.8319`;
- PGD adversarial training: PGD-20 accuracy `0.719` при ε = 0.1;
- выполнена targeted-ветка атак;
- выполнены бонусные задачи 7.1, 7.2, 7.4 и 7.5.

Notebook прошёл полный `Restart & Run All` с `FAST_MODE = False`.
