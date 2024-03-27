# Nezaplacené objednávky

Pracujete na velkém e-shopu a vaším úkolem je z nezaplacených objednávek vybrat všechny identifikátory a e-maily zákazníků pro zpracování dalšími systémy.

Vycházejte ze šablony na GitHubu cviceni-nezaplacene-objednavky.

Upravte soubor app.js tak, aby nachystal dvě nová pole identifikatory a emaily.

Pole const identifikatory = []a const emaily = [] jsou již předpřipravené. Upravte části za rovnítky. Využijte metodu map na poli nezaplaceneObjednavky.

Zařiďte, aby v prvním poli identifikatory byly pouze čísla, jednotlivá id z původního pole nezaplaceneObjednavky. Představte si, že čísla bude zpracovávat skladový systém, který je potřebuje přesně v této podobě.

V druhém poli by měly být pouze řetězce, jména s e-maily zákazníků ve formátu Jméno <jmeno@server.cz>, aby se daly snadno zpracovat e-mailovým serverem.

Poslední dva předchystané řádky nijak neupravujte. Představte si, že místo nich bude jednou kód, který předá vámi vytvořená pole dalším systémům.

processEmails(emaily);
processIdentifiers(identifikatory);
