# MmapPad

Универсальный просмотрщик и редактор больших файлов на основе memory-mapped files.

## Статус
Ранняя стадия разработки. Архитектура и контракты.

## Технологии
- .NET 8 (WinForms)
- Microsoft.Extensions.Hosting
- Serilog
- xUnit + Shouldly

## Структура
- `MmapPad.Abstractions` — интерфейсы и модели (без зависимостей от UI)
- `MmapPad.Core` — реализация сервисов
- `MmapPad.WinForms` — десктопное приложение
- `MmapPad.Tests` — юнит-тесты ядра

## Сборка
```bash
dotnet build
```

## Лицензия
MIT
