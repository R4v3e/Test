# WERSJA BUILD_v2_0 Działa na bazie .xml nie na folderach! zdjęcia dodawane są poprzez wstawienie pliku imageX.jpg do folderu imagefolder, gdzie X oznacza numer pytania
# oraz wpisanie nazwy zdjęcia w bazie przy 
"\<questions\> \<question\> \<answers\> \<image\> \<name\>tutaj nazwa zdjęcia</name></image></answers></question></questions>" 
W wersji build for linux \test_Data\StreamingAssets jest zamienione na \test_linux_Data\StreamingAssets<br />
<br />
\test_Data\StreamingAssets - main asset folder <br />
\test_Data\StreamingAssets\YOURFOLDER - folder na pytania <br />
\test_Data\StreamingAssets\YOURFOLDER\plikX - folder na pytania nr. X<br />
\test_Data\StreamingAssets\YOURFOLDER\plikX\pytanie.txt - dokument txt z pytaniem<br />
\test_Data\StreamingAssets\YOURFOLDER\plikX\odp1-3.txt - dokument txt z odpowiedzia (pierwsza linia na pytania. druga linia na punkty (TYLKO Argumenty INT !!!!!)<br />
\test_Data\StreamingAssets\YOURFOLDER\plikX\image.jpg - opcjonalny plik jpg dodawany do pytania<br />
<br />
\test_Data\StreamingAssets\Questions\settings.txt - dokument w ktorym okreslamy ilosc pytan oraz nazwe folderu z pytaniami <br />
  1. linijka ilość pytań do wytświetlenia; (nie uzywac wiekszej liczby niz ilosc folderow plikX!)<br />
  2. linijka nazwa folderu  (YOURFOLDER);<br />
\test_Data\StreamingAssets\standardimage.jpg - standardowy obraz uzywany kiedy nie ma okreslonego zdjecia dla danego pytania<br />
