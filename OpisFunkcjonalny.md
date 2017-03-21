# Ktulu, Wizja Projektu

## Cel:

Stworzenie aplikacji mobilnej wspomagającej uczestników gry towarzyskiej Ktulu. Aplikacja ułatwi rozgrywkę, w szczególności tym, którzy spotykają się z mieszkańcami Bum-Bum Town po raz pierwszy. Pomoże także rozpowszechnić tę grę, z ktorej wiele osób rezygnuje z powodu bardzo skomplikowanych zasad.

## Grupa docelowa:

Aplikacja jest przeznaczona zarówno dla zapalonych graczy Ktulu, którzy znają i kochają tę grę od lat, jak i tych, którzy z Ktulu nie mają doświadczenia, lecz słyszeli o dobrej zabawie jaką ta gra gwarantuje i chcieliby ją wypróbować w gronie znajomych.

Początkujący gracz może czuć się przytłoczonym liczbą i złożonością reguł do Ktulu. Nawet w gronie osób, które grę znają i chętnie wytłumaczą te reguły, nowy gracz może czuć się zagubiony lub martwić się, że spowalnia rozgrywkę. Nasza aplikacja uprości i skróci proces opanowywania tych skomplikowanych zasad, pozwalając każdemu na dołączenie do rozgrywki Ktulu – w roli gracza, czy nawet Manitou.

Weterani gry też skorzystają na aplikacji. Dostępność pod zasięgiem dłoni wszystkich reguł gry i zasad dotyczących poszczególnych kart ułatwi mieszkańcom strategizowanie. Natomiast Manitou nie będzie musiał polegać na zawodnej pamięci przy rozstrzyganiu poszczególnych kroków gry bądź sporów między graczami. Co więcej, rola Manitou, będąc najbardziej skomplikowaną rolą w rozgrywce Ktulu, będzie szczególnie wspomagana przez aplikację, kierując prowadzącego przez kolejne fazy dnia i nocy.

Od użytkowników aplikacja wymaga co najmniej jednego urządzenia mobilnego z aplikacją oraz kilku chętnych znajomych. Jeśli nie każdy gracz ma własny telefon z aplikacją, mogą się przydać wydrukowane karty do gry, ale nie są one konieczne.

## Funkcje:

- *Tutorial wprowadzający podstawy rozgrywki dla mieszkańca.* Interaktywny tutorial przedstawi nowemu użytkownikowi aplikacji skrócony opis gry wraz z najważniejszymi zasadami oraz zaprezentuje elementy interfejsu użytkownika, wyjaśniając jak z nich korzystać.

- *Tutorial wyjaśniający rolę Manitou.* Interaktywny tutorial przedstawi użytkownikowi aplikacji opis tych zasad gry, które Manitou musi znać by skutecznie prowadzić rozgrywkę. Przeprowadzi użytkownika przez przykładowy cykl noc-dzień wyjaśniając po drodze dostępny interfejs.

- *Podręcznik zawierający pełne zasady gry.* Zasady będą dostępne w formie kilku rozdziałów opisujących ogólne zasady oraz listy wszystkich dostępnych kart dla graczy. Odnośniki między rozdziałami podręcznika i wyszukiwarka słów kluczowych wspomoże wygodne i efektywne przeszukiwanie zasad.

- *Moduł prowadzenia gry dla Manitou.*

    - *Wybór kart.* Po wczytaniu liczby graczy, aplikacja informuje Manitou po ile kart z każdej frakcji należy wybrać. Manitou ma możliwość zmiany tego podziału przed wyborem kart. Następnie aplikacja proponuje losowy zbiór kart pasujący do wybranego podziału na frakcje. Manitou znowu może zaakceptować proponowane rozdanie, bądź dokonać dowolnych zmian. By karty rozdać, Manitou ma dwie możliwości – może rozdać fizyczne karty jeśli takie są dostępne, albo skorzystać z rozdawacza kart dostarczonego przez aplikację.

        - Wspomaganie rozdawania kart pozwala na przypisanie każdej osobie roli w grze. Pierwszy gracz dostaje telefon, na którym widzi guzik z napisem „Pokaż kartę”. Po naciśnięciu guzika, ujawnia się jego karta wraz z jej tekstem. Jest też guzik „Ukryj kartę”, który zastępuje ekran napisem „Przekaż telefon następnej osobie” i ponownie guzikiem z napisem „Pokaż kartę”. Gracze przekazują telefon od osoby do osoby póki każdy nie zobaczy swojej roli. Ostatni gracz, po przeczytaniu i ukryciu swojej karty, zobaczy napis „Oddaj telefon Manitou”.

        - Aplikacja będzie pamiętała kolejność rozdawania kart, dzięki czemu Manitou może zawsze sprawdzić który gracz ma jaką rolę, bez potrzeby pytania graczy.

        - Jeśli rozdane zostały fizyczne karty, Manitou ma możliwość wprowadzenia do aplikacji kolejności, w której je rozdał, żeby mieć dostęp do funkcji z poprzedniego podpunktu.

    - *Przebieg gry.* Po rozpoczęciu gry, aplikacja prowadzi Manitou przez poszczególne fazy dnia i nocy.

        - *Kolejność budzenia.* O ile aplikacja wie jakie karty zostały rozdane w aktualnej rozgrywce, każdej nocy będzie w odpowiedniej kolejności informowała Manitou, które frakcje bądź postacie powinny być obudzone. Po obudzeniu frakcji bądź postaci, aplikacja daje Manitou informacje o tym, co frakcja/postać powinna zrobić tej nocy. Ta funkcja uwzględnia fakt, że niektóre postacie nie budzą się każdej nocy. Na przykład Hazardzista budzony jest dopiero od drugiej nocy. 

        - *Pamięć stanu gry.* W każdym kroku, Manitou jest proszony o informacje dotyczące możliwych zmian w stanie gry. Aplikacja zapamiętuje i uwzględnia w swoich funkcjach ten stan. Na przykład:

            - Nie będzie budzić osób, które poszły pić z Opojem bądź Pijanym Sędzią.

            - Pamięta, który gracz ma aktualnie posążek.

            - Pamięta, którzy gracze są jeszcze w grze.

            - Pamięta, które osoby były chronione przez Ochroniarza.

            - Pamięta ile razy Ufolom udało się wysłać sygnał.

            - itp.

        - *Dzień.* Dostępne są funkcje Pojedynek, Przeszukiwanie i Wieszanie. Każda z tych funkcji prowadzi Manitou przez odpowiedni proces, przypominając zasady i oznajmiając kiedy powinno zostać przeprowadzone głosowanie, oraz jak interpretować oddane głosy.

        - *Sprawdzanie warunków końca gry.* Aplikacja, korzystając z zapamiętanego stanu, w odpowiednich momentach sprawdza, czy doszło do końca gry. Na przykład:

            - Na początku każdego dnia, jeśli posążek jest w posiadaniu miastowego, ogłoszone jest zwycięstwo miastowych. Od trzeciego poranka, jeśli posążek jest w posiadaniu bandyty, ogłoszone jest ich zwycięstwo.

            - Po śmierci dowolnej postaci, sprawdzane jest czy była ona ostatnim nie-Indianinem. Jeśli tak jest, to ogłoszone jest zwycięstwo Indian (chyba, że ta osoba posiadała posążek i została otruta przez Szamankę – wtedy wygrywa miasto).

            - Jeśli Ufole nadały swój trzeci sygnał, ogłoszone jest ich zwycięstwo.

            - itp.

    - Efekty dźwiękowe. Gra będzie akompaniowana przez proste efekty dźwiękowe. Na przykład:

        - Pianie koguta na początku dnia.

        - Proste tematy melodyczne pasujące do poszczególnych frakcji gdy są one budzone bądź gdy ogłoszone jest ich zwycięstwo.

        - Dźwięki strzałów po zakończonym pojedynku.

- Moduł dla gracza. Te funkcje wymagają połączenia sieciowego z urządzeniem Manitou.

    - Odbiór karty. Gracz nie musi dostać fizycznej karty, bądź korzystać z automatycznego rozdawacza kart dostępnego w module dla Manitou. Karta zostaje przesłana do gracza sieciowo (lub zeskanowana kodem QR z ekranu urządzenia Manitou w początkowych wersjach) i w każdej chwili gracz może sprawdzić jaką ma rolę.

    - Głosowanie i wybory. W przypadku tajnych głosowań i wyborów w nocy, gracz nie musi wskazywać na wybraną osobę, może do Manitou wysłać informację przez aplikację.

    - Przypomnienia. W trakcie dnia lub nocy, aplikacja przypomina graczowi jakie ma w danej chwili możliwości (za czym głosuje, czy może zacząć pojedynek, czy może odrzucić pojedynek), jaki jest jego cel oraz czy posiada posążek.
    
    - Personalizacja interfejsu i wyświetlanych komunikatów ze wgledu na frakcję do której przynależy uczestnik

- Automatyczny Manitou. Jeśli każdy gracz posiada własny telefon z aplikacją, możliwa jest gra bez Manitou. Wymaga to jednak ustalenia i zaimplementowania kilku protokołów, które nie są uwzględnione w oficjalnych zasadach Ktulu. Na przykład gracze muszą potrafić samemu rozpocząć głosowania na przeszukiwanie i wieszanie.

## Wykluczenia:
Nasza aplikacja na pewno nie będzie umożliwiała rozgrywki wirtualnej. Chcemy zachować najważniejsze wartości gier towarzystkich takich jak Ktulu czy Mafia, jakimi są między innymi integracja, wspólne spędzanie czasu, rozwijania umiejętności retorycznych.
