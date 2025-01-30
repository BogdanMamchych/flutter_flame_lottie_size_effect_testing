# flutter_flame_lottie_size_effect_testing

Тестування ефекту SizeEffect на Flame.

## Опис

SizeEffect - ефект, який відповідає за зміну розміру:
SizeEffect.by() - змінює розмір анімації відносно поточного розміру.
Наприклад: Якщо поточний розмір дорівнює Vector2(100, 100), тоді після застосування SizeEffect.by(Vector2(50, -10)), розмір буде Vector2(150, 90);
УВАГА: При спробі зменшити поточний розмір до від'ємних значень (наприклад, якщо поточне значення було Vector2(10, 10), а після застосування ефекту, отрималися від’ємні значення), тоді поточний розмір буде зафіксовано на нульовому рівні.
Важливо: Компонент повинен підтримувати зміну розміру (size), щоб ефект працював коректно.
SizeEffect.to() - змінює поточний розмір анімації.
Наприклад: Якщо поточний розмір дорівнює Vector2(100, 100), тоді після застосування SizeEffect.to(Vector2(50, 10)), поточний розмір буде Vector2(50, 10).
УВАГА: Значення НЕ МАЮТЬ БУТИ ВІД'ЄМНИМИ - ЕФЕКТ НЕ СПРАЦЮЄ;

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
