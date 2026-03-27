<h1>Прототип системы детекции уборки столиков по видео</h1>
<h2>1. Назначение</h2>
  <h3><h3>

<h3>После завершения в папке results/ появятся:output.mp4 — видео с визуализацией состояний столика;events.csv (если реализовано) — таблица событий;report.txt (если реализовано) — краткий текстовый отчёт со средним временем задержки.<h3>

### Пример запуска

Положите видео в `data/video1.mp4`, установите зависимости и запустите скрипт:

```bash
pip install -r requirements.txt
python main.py --video data/video1.mp4 --output results/output.mp4

<img width="1906" height="1048" alt="image" src="https://github.com/user-attachments/assets/d3239011-1923-460e-9df5-132d115296ec" />
<h2>1. После выделения рамки на изображении нажмите ENTER</h2>
![img2](https://github.com/user-attachments/assets/03945a27-d6de-498f-acc7-83559e7f3b99)

