## Правила типографа по порядку выполнения

| № | Имя | Название | Индекс | Вкл. |
|--:|-----|----------|-------:|:----:|
| 1. | `common/html/stripTags` | Удаление HTML-тегов | 5 |  |
| 2. | `common/sym/copy` | (c) → ©, (tm) → ©, (r) → ™ | 10 | ✓ |
| 3. | `common/sym/hellip` | ... → … | 20 | ✓ |
| 4. | `ru/dash/to` | Дефис перед то, либо, нибудь, ка, де, кась | 30 | ✓ |
| 5. | `ru/dash/izza` | Дефис между из-за | 33 | ✓ |
| 6. | `ru/dash/izpod` | Дефис между из-под | 35 | ✓ |
| 7. | `ru/dash/koe` | Дефис после кое и кой | 38 | ✓ |
| 8. | `ru/dash/taki` | Дефис между верно-таки и т.д. | 39 | ✓ |
| 9. | `common/html/url` | Расстановка ссылок | 200 | ✓ |
| 10. | `common/space/delTrailingBlanks` | Удаление пробелов в конце строк | 505 | ✓ |
| 11. | `common/space/replaceTab` | Замена табов на пробелы | 510 | ✓ |
| 12. | `common/space/trim` | Удаление пробелов в начале и в конце текста | 530 | ✓ |
| 13. | `common/space/delRepeatSpace` | Удаление повторяющихся пробелов | 540 | ✓ |
| 14. | `common/space/delRepeatN` | Удаление повторяющихся переносов строки (не более двух) | 545 | ✓ |
| 15. | `common/space/delBeforePunctuation` | Удаление пробелов перед знаками пунктуации | 550 | ✓ |
| 16. | `common/space/afterPunctuation` | Пробел после знаков пунктуации | 560 | ✓ |
| 17. | `ru/nbsp/beforeParticle` | Неразрывный пробел перед ли, ль, же, бы, б | 570 | ✓ |
| 18. | `common/delDoublePunctiation` | Удаление двойной пунктуации | 580 | ✓ |
| 19. | `ru/nbsp/afterShortWord` | Неразрывный пробел после короткого слова | 590 | ✓ |
| 20. | `common/nbsp/afterShortWord` | Неразрывный пробел после короткого слова | 590 | ✓ |
| 21. | `common/space/delBeforePercent` | Удаление пробела перед % | 600 | ✓ |
| 22. | `ru/dash/weekday` | Тире между днями недели | 600 | ✓ |
| 23. | `ru/dash/month` | Тире между месяцами | 610 | ✓ |
| 24. | `ru/nbsp/afterNum` | Неразрывный пробел после № и § | 610 | ✓ |
| 25. | `common/nbsp/afterPara` | Неразрывный пробел после § | 610 | ✓ |
| 26. | `ru/nbsp/page` | Неразрывный пробел перед стр., гл., рис., илл. | 610 | ✓ |
| 27. | `ru/dash/main` | Дефис на тире | 620 | ✓ |
| 28. | `common/nbsp/beforeShortLastWord` | Неразрывный пробел перед последним коротким словом в предложении | 620 | ✓ |
| 29. | `ru/nbsp/beforeShortLastWord` | Неразрывный пробел перед последним коротким словом в предложении | 620 | ✓ |
| 30. | `ru/quot` | Расстановка кавычек | 700 | ✓ |
| 31. | `common/html/pbr` | Расстановка тегов p и br | 700 |  |
| 32. | `common/html/nbr` | Замена перевода строки на тег br | 710 |  |
| 33. | `ru/optalign/quot` | Висячая пунктуация для открывающей кавычки | 1000 |  |
| 34. | `ru/optalign/bracket` | Висячая пунктуация для открывающей скобки | 1001 |  |
| 35. | `ru/optalign/comma` | Висячая пунктуация для запятой | 1002 |  |
| 36. | `common/sym/plusMinus` | +- → ± | 1010 | ✓ |
| 37. | `common/sym/cf` | Добавление ° к C и F | 1020 | ✓ |
| 38. | `ru/nbsp/m` | m2 → м², m3 → м³ и неразрывный пробел | 1030 | ✓ |
| 39. | `common/sym/times` | x → × | 1050 | ✓ |
| 40. | `ru/nbsp/xxxx` | Неразрывный пробел после XXXX (2012 г.) | 1060 | ✓ |
| 41. | `ru/nbsp/yy` | г.г. → гг. и неразрывный пробел | 1080 | ✓ |
| 42. | `common/sym/cc` | Удаление лишних точек и пробелов в вв. | 1090 | ✓ |
| 43. | `ru/nbsp/ooo` | Неразрывный пробел после OOO или ОАО | 1100 | ✓ |
| 44. | `ru/nbsp/but` | Расстановка запятых и неразрывного пробела перед а и но | 1110 | ✓ |
| 45. | `common/sym/fraction` | 1/2 → ½, 1/4 → ¼, 3/3 → ¾ | 1120 | ✓ |
| 46. | `common/sym/arrow` | -> → →, <- → ← | 1130 | ✓ |
| 47. | `ru/money/euro` | €100 → 100 € | 1140 | ✓ |
| 48. | `ru/money/dollar` | $100 → 100 $ | 1140 | ✓ |
| 49. | `common/exclamationQuestion` | !? → ?! | 1140 | ✓ |
| 50. | `ru/money/ruble` | 1 руб. → 1 ₽ | 1145 |  |
| 51. | `common/exclamation` | !! → ! | 1150 | ✓ |
| 52. | `common/nbsp/dpi` | Неразрывный пробел перед lpi, dpi | 1150 | ✓ |
| 53. | `common/repeatWord` | Удаление повтора слова | 1200 |  |
| 54. | `ru/number/ordinals` | N-ый, -ой, -ая, -ое, -ые, -ым, -ом, -ых → N-й, -я, -е, -м, -х (25-й) | 1300 | ✓ |
| 55. | `ru/date/main` | Преобразование дат YYYY-MM-DD к виду DD.MM.YYYY | 1300 | ✓ |
| 56. | `ru/date/weekday` | 2 Мая, Понедельник → 2 мая, понедельник | 1310 | ✓ |
| 57. | `common/nbsp/nowrap` | Заменять неразрывный пробел на обычный пробел в тегах nowrap и nobr | 1400 | ✓ |