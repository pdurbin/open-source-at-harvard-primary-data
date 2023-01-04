# Open Source at Harvard Primary Data

These are the JSON files downloaded and used by the code at https://github.com/IQSS/open-source-at-harvard

They are also uploaded to the [Open Source at Harvard dataset][] as a double-zipped file (until [#8029][] is addressed) using a procedure that looks something like this:

    cp -r YYYY-MM-DD primary-data
    zip -r primary-data.zip primary-data -x '**/.*' -x '**/__MACOSX'
    zip -r outer.zip primary-data.zip -x '**/.*' -x '**/__MACOSX'

[Open Source at Harvard dataset]: https://doi.org/10.7910/DVN/TJCLKP
[#8029]: https://github.com/IQSS/dataverse/issues/8029
