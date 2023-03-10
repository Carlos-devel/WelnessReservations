# Nefunkční požadavky
 1. Systém bude responzivní, resp. čas mezi akcí uživatele a prvním projevením systému bude maximálně 1s.
 2. Systém bude umožňovat práci v readonly offline režimu
 3. Výpadek systému může být maximálně 1 hodina
 4. Ukládané údaje o uživatelých se řidí GDPR
 5. Zaměstnanec, který bude využívat systém, k němu bude přistupovat pomocí vygenerovaného kódu a minimálně 16 místného hesla dle vlastního výběru obsahující číslice, velká i malá písmena a vybrané speciální znaky
 6. Klient musí být registrovaný.
 7. Klient provádí registraci sám pokud se jedná o fyzickou osobu. Pokud je klientem právnická osoba, pak musí registraci provést fyzicky na pobočce. Zaměstnanec získává přihlašovací údaje od správce systému
 8. Správce systému nemá přistup k heslům uživatelů/zaměstnanců 
 9. Rezervace na wellness procedury se dají vytvářet/rušit maximálně do půlnoci předchozího dne
 10. Klientem může být pravnická i fyzická osoba
 11. Zdravotní omezení nejsou omezením pro výběr procedury. Klient bude pouze varován.
 12. Systém bude zasílat notifikace prostřednicvím emailu klientům
 13. Klientské emaily jsou zasílány v momentě když vytvoří objednávku, při změně ze strany zaměstnance a den před zahájením 24 hodin
 14. Klient má možnost vybrat kdo bude provádět danou proceduru (rezervace osoby na proceduře)
# Funkční požadavky
1. Klient má možnost změny přihlašovacích a fakturačních údajů
2. Klient může vytvářet rezervace na jednotlivé wellness procedury
3. Klient může upravovat/rušit rezervace na jednotlivé wellness procedury 
4. Klient má možnost provést registraci
5. Zaměstnanec navrhuje nové časy pro rezervace
6. Zaměstnanec upravuje rezervace klienta
7. Zaměstnanec převádí rezervaci na započatou proceduru
8. Zaměstnanec upravuje seznam zdravotních omezení danné procedury
9. Klient (fyzická osoba) může zadat a editovat svá zdravotní omezení
# Doménové požadavky
1. Systém bude ke svému běhu využívat webové rozhraní
2. Bude použit Docker 
3. Bude využita relační databáze
4. Veškeré stránky systému budou renderovány na serveru
5. apka bude monolith
