# rutube-video-captioning

Проект решает задачу автогенерации описания к видео на сервисе RuTube

# Архитектура решения

![Архитектура](https://github-production-user-asset-6210df.s3.amazonaws.com/61351134/271807159-6b5c9b29-c0da-4e43-b148-a8d651b9aa38.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20231001%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231001T033737Z&X-Amz-Expires=300&X-Amz-Signature=5b861136006557f4df68a67daa6031d7e68dd538aa26b5a3396d34a510cb80d1&X-Amz-SignedHeaders=host&actor_id=61351134&key_id=0&repo_id=698162921)

# Пример

## Реальное

```
в этом выпуске шоу “ стендап гороскоп ” карина салихова расскажет про то , что ждет в 2022 году представителей одного из самых упрямых знаков зодиака – тельцов .
```

## Предсказанное

```
в новом выпуске шоу « стендап гороскоп » расскажет про расскажет про представителей знака , что ждет представителей знака в 2022 году .
```

# Использованные технологии

- Google Colab
- PyTorch
- Figma
- CNN / RNN
- Seq2seq

# Описания файлов

- [Модель для генерации описания по текстовой расшифровке](https://github.com/llitone/rutube-video-captioning/blob/main/text-captioning.ipynb)
- [Модель для генерации описания по кадрам из видео](https://github.com/llitone/rutube-video-captioning/blob/main/video-captioning.ipynb)
- [Модель для суммаризации текста из двух двух моделей для получения окончательного описания](https://github.com/llitone/rutube-video-captioning/blob/main/video-with-text-captioning.ipynb)
