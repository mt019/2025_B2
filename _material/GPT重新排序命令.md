我這邊有一份 Markdown 詞彙筆記，每個條目都有「編號 + 標題」，現在我希望你幫我依照主題邏輯重排順序。請你幫我分析以下標題，然後回傳一個 Python 陣列的形式：

- 陣列格式需為：new_order = [⋯] 並用註解標明主題（例如 # 購物類）
- 避免遺漏或重複，所有數字都要出現一次且只出現一次！！
- 不允許重複，不允許遺漏！！！

這是清單（每一行是編號和詞語）：

1: ## 1. sobald
2: ## 2. egal wie
3: ## 3. vorausgesetzt
4: ## 4. hingegen
5: ## 5. gelten
7: ## 7. selbstverständlich
8: ## 8. davon ausgehen
9: ## 9. zustehen
10: ## 10. einige behaupten
11: ## 11. daher gilt
12: ## 12. übernehmen
13: ## 13. ausnutzen
14: ## 14. benötigen
15: ## 15. verzichten
16: ## 16. ermöglichen
17: ## 17. vorhanden
18: ## 18. vereinbar sein mit
19: ## 19. schaffen
20: ## 20. ausstrahlen
21: ## 21. beweisen
22: ## 22. Hast du dazu schon (eine) Forschung gemacht?
23: ## 23. Hast du Beweise?
24: ## 24. rücksichtslos
25: ## 25. naturverbunden
26: ## 26. umweltbewusst
27: ## 27. die Ressource
28: ## 28. das Gleichgewicht
29: ## 29. künstliche Intelligenz
30: ## 30. Ich habe mich vielleicht nur früh registriert, aber ich benutze es kaum
31: ## 31. Vielleicht ist mein Level gestiegen, weil ich oft einen Voice-Raum eröffnet habe
32: ## 32. viele Stufen
33: ## 33. sehr entwickelt
34: ## 34. Nur so kann ich lernen und mich verbessern
35: ## 35. Genau
36: ## 36. Ich habe Angst, etwas Falsches zu sagen, deshalb traue ich mich nicht zu sprechen
37: ## 37. Aber nur unter Druck mache ich Fortschritte
38: ## 38. Zum Beispiel hat gerade jemand, der Musik macht, mit mir über das Gitarrespielen gesprochen – aber ich habe gar nichts verstanden. Ich war nervös, unter Druck und fand es peinlich. Danach habe ich einige Vokabeln dazu gelernt – und so habe ich Fortschritte gemacht.
39: ## 39. gar nichts verstehen
40: ## 40. nervös sein
41: ## 41. unter Druck sein / stehen
42: ## 42. es peinlich finden
43: ## 43. Vokabeln lernen
44: ## 44. Fortschritte machen
45: ## 45. In der Realität oder in Prüfungen werden solche Wörter vielleicht nicht so oft verwendet
46: ## 46. Freunde oder Bekannte
47: ## 47. Es ist schwer, online Freunde zu finden
48: ## 48. Es ist auch schwierig, einen Sprachpartner zu finden
49: ## 49. Ich brauche jemanden, der besser ist als ich
50: ## 50. Ich brauche am meisten jemanden, der mit mir Deutsch spricht und mir hilft, mich zu verbessern
51: ## 51. Ich habe dasselbe Problem wie du
52: ## 52. Wenn ich viele Sprachpartner hätte, wäre ich sehr froh
53: ## 53. Ich hoffe, dass ich Glück habe
54: ## 54. Ich hoffe es
55: ## 55. Ich fürchte, ich kann nicht
56: ## 56. Ich fürchte, ich muss schlafen
57: ## 57. Ich habe keinen Akzent und spreche sehr fließend
58: ## 58. Meine Internetverbindung ist nicht so gut
59: ## 59. angeboren
60: ## 60. bloß
61: ## 61. Anwesenheit
62: ## 62. angemessen
63: ## 63. Weisheit
64: ## 64. genügsam
65: ## 65. die Würde
66: ## 66. einleiten
67: ## 67. die Störung
68: ## 68. auftreten
69: ## 69. sich erholen
70: ## 70. sich regulieren
71: ## 71. eingreifen
72: ## 72. Eingriff
73: ## 73. das duale Studium
74: ## 74. im Wald wohnen
75: ## 75. singen
76: ## 76. Mogli / Das Dschungelbuch
77: ## 77. alt (im Kontext: Film / Serie)
78: ## 78. der Kongo
79: ## 79. Mowgli
80: ## 80. Gesundheit
81: ## 81. Gute Besserung
82: ## 82. keine Ahnung haben
83: ## 83. gegenüber
84: ## 84. bereitwillig
85: ## 85. untertan
86: ## 86. gelten als



請幫我重新排列，並用 Python 陣列格式回傳。