# WordComposerMicroservice

> [!CAUTION]
> Это тестовый проект для презентации. Его запуск не подразумевается из-за комплексности, хотя это и возможно при должном желании 😃

> [!NOTE]  
> Данное приложение помогает обрабатывать **англоязычные** слова, которые в последствии получают **перевод, транскрипцию, значение, а также изображение для создания карточки слова**.

> [!TIP]
> Требуется всё необходимое:
> * GITHUB CLOUD CONFIG SETTINGS 
> * API KEYS_SECRETS(https://dictionaryapi.dev/, https://unsplash.com/, https://imgbb.com/)
> * S3 Container
> * Self-hosted LibreTranslate in Docker
> * Postgresql DB
> * Elastic-Stack for logging(Optional)
> * minikube -> strimzi config with 3 kafka topics: initial-topic, image-handler-topic, card-representor-topic