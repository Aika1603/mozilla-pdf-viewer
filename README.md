
# FOR LARAVEL PROJECT :disguised_face:

Steps :
* copy folder assets ke /root_project/public/
* tambahkan routing ke routes/web.php (lihat sourcode di bawah)
* copy /resources ke folder /root_project/resources

## update your routing 
```
Route::get('/pdf-viewer', function () {
        return view('pdf-viewer');
    })->name('pdf-viewer');
```

## how to use on your view
```
<iframe frameborder="0" src="{{ url('pdf-viewer') }}"?file={{ PDF_LINK }}" width="100%" style="height:500px;"></iframe>
```

> Salam satu coding :coffee: