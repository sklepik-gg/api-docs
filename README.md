# sklepik.gg API Documentation

Oficjalna dokumentacja API dla **sklepik.gg**.

## 📦 O projekcie

API sklepik.gg umożliwia łatwą integrację systemu płatności w Twoich własnych projektach, aplikacjach lub sklepach internetowych.  
Dzięki temu możesz przyjmować płatności, zarządzać zamówieniami i automatyzować procesy bezpośrednio ze swojego oprogramowania.

---

## ✨ Główne możliwości

- Obsługa płatności online (automatyzacja zamówień)
- Integracja z własną stroną, botem lub systemem
- Sprawdzanie statusu transakcji i historii zakupów
- Powiadomienia o zmianach statusu zamówienia (webhooki)
- Bezpieczne uwierzytelnianie i pełna dokumentacja endpointów

---

## 🚀 Jak zacząć

1. **Uzyskaj dostęp do API**  
   Załóż konto na [sklepik.gg](https://sklepik.gg) i wygeneruj swój klucz API.

2. **Sprawdź autoryzację**  
   Wszystkie żądania wymagają nagłówka `Authorization` z Twoim kluczem API.

3. **Wywołaj pierwszy endpoint**  
   Przykład żądania pobierającego status zamówienia:
   ```bash
   curl -X GET "https://api.sklepik.gg/orders/{order_id}" \
   -H "Authorization: Bearer YOUR_API_KEY" 
   ```

## 🤝 Wsparcie

Jeśli masz pytania lub chcesz zgłosić błąd, otwórz issue lub napisz na **support@sklepik.gg**

📝 Licencja
Projekt dostępny na licencji MIT.

sklepik.gg — Najprostszy sposób na wdrożenie płatności do własnego projektu!
