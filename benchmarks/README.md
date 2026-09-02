# Бенчмарки

Для запуска установите `BenchmarkOneScript`:

```powershell
opm install benchmark
```

Запуск всех бенчмарков:

```powershell
benchos run .\benchmarks
```

Запуск отдельного набора:

```powershell
benchos run .\benchmarks\IPАдреса.os
```

Короткий диагностический запуск:

```powershell
benchos run --iterationCount 2 --warmupCount 1 .\benchmarks
```
