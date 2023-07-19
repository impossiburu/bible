# bible
HOLY BIBLE Protestant version (true bible book list)

+ json format
+ synodal
+ russian language

Example to use:
```php
// Getting all chapter from the first bible book
foreach ($bibleArray['Books'][0]['Chapters'] as $chapter) {
    echo '<p><b>Глава ' . $chapter['ChapterId'] . '</b></p>';
    foreach ($chapter['Verses'] as $verses) {
        echo '<p>' . $verses['VerseId'] . '. ' .  $verses['Text'] . '</p>';
    }
}
```
