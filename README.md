extract
=======

&lt;?php $zip = new ZipArchive; if ($zip->open('test.zip') === TRUE) {   $zip->extractTo('/my/destination/dir/');   $zip->close();   echo 'ok'; } else {   echo 'failed'; } ?>
