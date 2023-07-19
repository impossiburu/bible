# bible
HOLY BIBLE Protestant version (true bible book list)
Bible in JSON
_____________________________

Example to use:
//Getting all chapters from the first bible book
foreach ($bibleArray['Books'][0]['Chapters'] as $chapter) {
    echo '<p><b>Глава ' . $chapter['ChapterId'] . '</b></p>';
    foreach ($chapter['Verses'] as $verses) {
        echo '<p>' . $verses['VerseId'] . '. ' .  $verses['Text'] . '</p>';
    }
}
