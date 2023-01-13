
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

> Salam satu coding :coffee: