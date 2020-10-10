# Produkcyjne środowiska wirtualizacyjne

## VMWare Workstation

VMware Workstation to branżowy standard do uruchamiania wielu systemów operacyjnych jako maszyn wirtualnych (VM) na jednym komputerze z systemem Linux lub Windows. Specjaliści IT, programiści i firmy, które tworzą, testują lub prezentują oprogramowanie dla dowolnego urządzenia, platformy lub chmury, polegają na Workstation.

### Sposoby licencjonowania

Aby uzyskać licencję na VMware Workstation trzeba kolejno uruchomić VMware Workstation, wprowadzić numer seryjny, wprowadzić klucz licencyjny, zarejestrować stację roboczą VMWare. Rejestracja VMWare Workstation zapewnia najnowsze informacje i ogłoszenia o produktach i usługach VMWare, a także daje 30 dni bezpłatnego wsparcia internetowego.

## XEN

Xen to maszyna wirtualna typu 1, zapewniająca usługi umożliwiające jednoczesne wykonywanie wielu systemów operacyjnych na tym samym sprzęcie komputerowym.

### Sposoby licencjonowania

XenServer korzysta z tego samego procesu licencjonowania, co inne produkty Citrix, w związku z czym wymaga zainstalowania ważnej licencji na serwerze licencji. Serwer licencji można pobrać z Citrix Licensing. XenServer (inny niż licencje XenApp/XenDesktop) jest licencjonowany na podstawie licencji na gniazdo. Alokacja licencji jest zarządzana centralnie i wymuszana przez autonomiczny serwer licencji Citrix, fizyczny lub wirtualny, w środowisku.

## Hyper-V

Oprogramowanie stosowane do wirtualizacji fizycznych maszyn, komputerów. Dzięki niemu można uruchamiać różne systemy operacyjne bez konieczności fizycznej ingerencji w już zainstalowany system operacyjny, na jednej fizycznej maszynie bez konieczności dzielenia dysku na partycje. Ta edycja zawiera odchudzoną wersję systemu Windows Server. Zasadniczo jest to Windows Server Core i jest przeznaczony do uruchamiania tylko roli Hyper-V. Jest przeznaczony do uruchamiania maszyn wirtualnych i niczego innego, ale można go dołączyć do domeny, co ułatwia zarządzanie. Korzystanie z niego daje pewne korzyści. Ponieważ jest odchudzony, ma mniej oprogramowania uruchomionego na serwerze. Oznacza to mniej aktualizacji i mniej oprogramowania, z którego może skorzystać osoba atakująca. Oznacza to również potencjalnie mniej zasobów używanych na serwerze. Jeśli ktoś ma w planach instalację systemu Windows Server Standard na maszynie wirtualnej przy użyciu funkcji Hyper-V, może warto, aby administrator skorzystał z edycji Standard dla rozwiązania do wirtualizacji. To daje więcej opcji później, jeśli zleceniodawca zmieni zdanie lub zmienią się wymagania. W przypadku Hyper-V, jeśli chcesz później dodać funkcje, jedynym wyborem może być ponowna instalacja innej edycji.


### Sposoby licencjonowania

Ponieważ jest to tylko rozwiązanie do wirtualizacji, firma Microsoft umożliwia bezpłatne pobranie go w wersji Standard.

# Wady i zalety wirtualizacji

Świat IT coraz bardziej aktywnie wkracza w wirtualizację. Organizacje decydują się na wirtualizację ze względu na różne korzyści, jakie zapewnia. Co więcej, wraz z pojawieniem się chmury nowe firmy wolą pracować w środowisku wirtualnym, ponieważ pomaga to zdalnym środowiskom pracy. Nie wszystko jest tak różowe, jak się wydaje. Wszystko ma swoje wady i zalety, w tym wirtualizację.

## Zalety wirtualizacji

### Wydajnie wykorzystuje sprzęt

Większość firm wydaje dużo kapitału na konfigurację swoich systemów i serwerów, ale ostatecznie efektywnie wykorzystuje tylko ułamek tego kapitału. Zamiast tego, jeśli zdecydują się na wirtualizację, mogą utworzyć wiele instancji na tym samym sprzęcie i wyodrębnić z niego maksymalną wartość. W ten sposób mogą obniżyć koszty sprzętu i osiągnąć wysoki poziom wydajności.

### Dostępne przez cały czas

Istotną zaletą wirtualizacji jest zezwalanie na stałą dostępność instancji wirtualnych. Największą zaletą jest tutaj możliwość przenoszenia wirtualnej instancji z jednej lokalizacji serwera do drugiej. Można to zrobić bez konieczności zamykania i ponownego uruchamiania procesów, które już działają. Dane nie zostaną utracone podczas procesu migracji. W związku z tym nie ma znaczenia, czy wystąpią nieplanowane przestoje, Twoja instancja będzie zawsze działać przez cały czas.

### Odzyskiwanie jest łatwe

Dzięki wystąpieniom wirtualnym na zdalnych serwerach duplikacja, tworzenie kopii zapasowych i odzyskiwanie jest również łatwiejsze. Poprzez nowe narzędzia, które zapewniają tworzenie kopii zapasowych i dublowanie danych niemal w czasie rzeczywistym, można mieć pewność, że w dowolnym momencie nie zostaną utracone żadne dane. W przypadku przestoju lub awarii mogą po prostu odebrać ostatnią zapisaną pozycję, która została odzwierciedlona w innej wirtualnej instancji. Zapewnia to ciągłość biznesową przez cały czas. Dzięki temu organizacje mogą osiągnąć najwyższą wydajność.

### Szybka i łatwa konfiguracja

Konfigurowanie fizycznych systemów i serwerów to czasochłonna sprawa. Musisz złożyć zamówienie i poczekać, aż zostanie przetworzone. Po zakończeniu poczekaj, aż produkty zostaną wysłane i skonfigurowane, co może zająć kilka godzin. Gdy już poprawnie wykona się wszystkie połączenia nadal trzeba zainstalować wymagany system operacyjny i oprogramowanie, które pochłania więcej godzin. Ogólnie rzecz biorąc, cały proces konfiguracji wymaga długiego oczekiwania, wartego dni lub nawet tygodni. Z drugiej strony, dzięki wirtualizacji, możesz w ciągu kilku minut rozpocząć produktywną konfigurację.

### Migracja do chmury jest łatwiejsza

Wiele organizacji nawet dziś stosuje metodologie starej szkoły. Robią to, ponieważ w przeszłości dokonali znacznych inwestycji, aby zapewnić, że ich systemy informatyczne zawsze działają. Przy obecnej fali transformacji cyfrowej organizacje chcą przejść do chmury, aby uzyskać różne korzyści. Wyzwaniem jest migracja tak dużej ilości danych dostępnych lokalnie. Wirtualizacja znacznie ułatwiłaby zadanie, ponieważ większość danych byłaby już dostępna na serwerze. W związku z tym migracja tego wszystkiego do chmury byłaby łatwiejsza.

## Wady wirtualizacji

### Wysoka inwestycja początkowa

Wirtualizacja jest pomocna, ale ma pewne wady, a jedną z głównych wad jest wysoki koszt inwestycji początkowej. Ta opcja rzeczywiście pomaga firmie obniżyć koszty operacyjne. Jednak początkowy koszt konfiguracji serwerów i pamięci masowej jest wyższy niż w przypadku zwykłej konfiguracji. Dlatego firmy potrzebują lat, zanim osiągną zysk, a następnie osiągną oszczędności i wyższą rentowność dzięki wirtualizacji. To zły zakład dla firm, które na początku decydują się na dużą konfigurację. Zamiast tego możnaby wybrać zwykłą konfigurację pulpitu, a następnie stopniowo przejść do wirtualizacji pulpitu.

### Dane mogą być zagrożone

Wirtualizacja może narazić dane na ataki lub nieautoryzowany dostęp. Jest to wyzwanie, jeśli dostawca usług nie ma odpowiednich rozwiązań zabezpieczających, które chroniłyby wirtualną instancję i dane. To fakt, szczególnie w przypadku wirtualizacji pamięci masowej.

### Szybka skalowalność to wyzwanie

Skalowanie wirtualizacji to pestka, ale nie tak bardzo, jeśli trzeba to zrobić w krótkim czasie. W przypadku konfiguracji fizycznej można szybko skonfigurować nowy sprzęt i skalę, nawet jeśli wiąże się to z pewnymi komplikacjami związanymi z początkową konfiguracją. W przypadku wirtualizacji zapewnienie wymaganego oprogramowania, bezpieczeństwa, wystarczającej ilości pamięci masowej i dostępności zasobów może być żmudnym zadaniem. Zajmuje to więcej czasu, niż można by się spodziewać, ponieważ w grę wchodzi dostawca zewnętrzny. Ponadto dodatkowy koszt związany ze zwiększonym wykorzystaniem zasobów jest kolejnym wyzwaniem do zarządzania.

### Wydajność

Prawdą jest, że wirtualizacja umożliwia optymalne wykorzystanie wszystkich zasobów. Zasoby związane z wirtualizacją są udostępniane. Te same zasoby, które mógł zużyć pojedynczy użytkownik, są teraz współdzielone między trzech lub czterech użytkowników. Całkowite dostępne zasoby mogą nie być dzielone równo lub mogą być współdzielone w pewnym stosunku, w zależności od wykonywanych zadań. Wraz ze wzrostem złożoności zadań rośnie zapotrzebowanie na wydajność systemu. Powoduje to znacznie dłuższy czas potrzebny do wykonania zadania.

### Niezamierzone działanie serwera

Niezamierzony rozrost serwerów jest głównym powodem niepokoju wielu administratorów serwerów i użytkowników. Konfiguracja serwera fizycznego pochłania czas i zasoby, podczas gdy serwer wirtualny można utworzyć w ciągu kilku minut. Za każdym razem, zamiast ponownie używać tego samego serwera wirtualnego, użytkownicy mają tendencję do tworzenia nowych serwerów, ponieważ daje im to szansę na nowy start. Administrator serwera, który powinien obsługiwać pięć lub sześć serwerów, musi obsługiwać ponad 20 serwerów wirtualnych. Może to spowodować poważne komplikacje w płynnym działaniu, a wymuszone zakończenie niektórych serwerów może również spowodować utratę danych.

# Sprzęt stosowany w środowiskach produkcyjnych

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce ut accumsan massa, nec porttitor est. Suspendisse potenti. Nam cursus et urna a dictum. Phasellus faucibus, nibh nec aliquam tristique, diam neque lacinia arcu, a sollicitudin nibh magna eu nisl. Sed a finibus quam. In faucibus vel nulla non rutrum. Cras sit amet urna quis massa laoreet imperdiet. In dignissim turpis hendrerit efficitur scelerisque. Aliquam pulvinar neque a enim porttitor, sed commodo quam fringilla. Cras fringilla sit amet nunc sit amet porta. Pellentesque bibendum elit id nisi consectetur, eget fermentum dui tristique. Sed sit amet blandit ex. Nulla molestie ullamcorper iaculis. Aenean sapien velit, commodo eu purus egestas, iaculis imperdiet dolor. Vivamus eget mi laoreet, convallis quam ac, tincidunt libero. Morbi finibus dui a metus dignissim bibendum eget mollis risus. 
