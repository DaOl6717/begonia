# begonia

Repo för Begoniagruppen!

För att kunna användare Firebase i appen måste du placera filen "google-services.json" under android/app/
Denna fil har jag av säkerhetskäl valt att inte lägga till i vårt repository då den innehåller en api nyckel vilken kan missbrukas av utomstående.
Kontakta därför Filip för att få tag på filen.

Utöver att lägga till google-services.json filen måste ni också köra kommandot flutterfire configure i root för projektet för att generera en fil som heter firebase_options.dart. För att kunna köra flutterfire kommandot måste ni installera Flutterfire CLI vilket ni kan göra genom att följa denna sida (ni behöver endast göra steg 1 och 2): https://firebase.google.com/docs/flutter/setup?platform=ios
