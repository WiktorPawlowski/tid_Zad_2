# 📄 Spotify – Dokumentacja Techniczna
## Wiktor Pawłowski
## Spis treści:
#### - Opis ogólny aplikacji
#### - Architektura techniczna
#### - Funkcjonalności aplikacji
#### - Warunki użytkowania i licencja
#### - API i integracje (opcjonalnie)
#### - Technologie użyte w projekcie

## 1. Opis ogólny aplikacji
### Spotify to multiplatformowa aplikacja strumieniująca muzykę z funkcjami społecznościowymi i inteligentnym rekomendowaniem treści. System umożliwia użytkownikom dostęp do milionów utworów, tworzenie własnych playlist, obserwowanie artystów oraz słuchanie muzyki offline.

## 2. Architektura techniczna

### Spotify działa w modelu klient-serwer, opartym na architekturze mikroserwisów. Składa się z następujących komponentów:
#### - Frontend: React Native (aplikacja mobilna), React (web), Electron (desktop)
#### - Backend: Node.js + Express, usługi w Pythonie (ML), Golang (przesył audio)
#### - Baza danych: PostgreSQL (użytkownicy, playlisty), Cassandra (logi, streamy), Redis (cache)
#### - Streaming audio: CDN + niestandardowy protokół streamingu
#### - Machine Learning: silnik rekomendacji w Pythonie (TensorFlow, Apache Spark)
#### - Autoryzacja: OAuth 2.0, tokeny JWT


## 3. Funkcjonalności aplikacji

### 🎧 Odtwarzanie i zarządzanie muzyką:
#### - Strumieniowanie utworów w czasie rzeczywistym (do 320 kbps)
#### - Obsługa trybu offline (dla subskrybentów premium)
#### - Kolejka odtwarzania, powtarzanie, losowe odtwarzanie

### 🔍 Wyszukiwanie i eksploracja:
#### - Wyszukiwanie po tytule, artyście, albumie, nastroju
#### - Sekcja „Odkrywaj tygodniowo” i „Radar premier”
#### - Inteligentne rekomendacje na podstawie historii słuchania

### 📁 Playlisty i biblioteka:
#### - Tworzenie i edytowanie playlist
#### - Obserwowanie playlist publicznych
#### - Możliwość zapisywania albumów i utworów w bibliotece

### 👥 Funkcje społecznościowe:
#### - Obserwowanie znajomych i artystów
#### - Udostępnianie utworów w mediach społecznościowych
#### - „Blend” – playlisty wspólne z innymi użytkownikami

### 🧠 Machine Learning:
#### - Algorytmy rekomendujące (Collaborative Filtering, NLP)
#### - Dynamiczna analiza gustu użytkownika
#### - Spersonalizowane playlisty generowane automatycznie

### 📱 Integracje i wieloplatformowość:
#### - Wersje na Android, iOS, Windows, macOS, Web
#### - Obsługa Spotify Connect (kontrola odtwarzania na innych urządzeniach)
#### - Integracja z Discordem, Instagramem, Google Maps, Apple Watch

## 4. Warunki użytkowania i licencja
### Spotify jest oprogramowaniem zamkniętym (proprietary software). Kod źródłowy aplikacji nie jest dostępny publicznie, a jej użycie reguluje komercyjna licencja użytkownika końcowego (EULA).
### ✅ Użytkownik może:
#### - Korzystać z aplikacji w ramach planu darmowego lub płatnego (Premium).
#### - Tworzyć playlisty, zapisywać treści i używać funkcji społecznościowych.
#### - Korzystać z aplikacji na wielu urządzeniach jednocześnie (zgodnie z planem).

### ❌ Użytkownik nie może:
#### - Modyfikować, dekompilować ani odtwarzać kodu źródłowego aplikacji.
#### - Udostępniać utworów poza platformą z naruszeniem licencji.
#### - Przechwytywać lub zapisywać streamowane utwory bez zgody Spotify.

### 📜 Link do licencji:
#### Spotify Terms of Use (Warunki użytkowania):
#### 🔗 https://www.spotify.com/legal/end-user-agreement/

### 📜 Fragment licencji:
#### "Spotify is a licensed streaming service. Content is made available for personal and non-commercial use only. You may not copy, redistribute, reproduce, record, transfer, perform or display to the public any part of the Spotify Service or the Content."

## 5. API i integracje (dla programistów)
### Spotify oferuje Spotify Web API, które umożliwia deweloperom:
#### - Pobieranie informacji o utworach, albumach, artystach i playlistach
#### - Zarządzanie biblioteką i odtwarzaniem użytkownika
#### - Odczyt danych analitycznych i preferencji muzycznych
### Dokumentacja API:
#### 🔗 https://developer.spotify.com/documentation/web-api/

## ✅ Instrukcje końcowe
### Ten dokument należy:
#### - Zapisać jako Spotify_Dokumentacja_Techniczna.pdf lub .md
#### - Umieścić w repozytorium GitHub Classroom jako dokument końcowy (cz.1 + cz.2)
#### - Upewnić się, że zawiera nagłówki, numerację, sekcje i specjalistyczny język techniczny
