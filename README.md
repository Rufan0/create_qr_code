# create_qr_code
Python vasitəsilə qr code yaratmaq


![python foto](https://i.imgur.com/9naUJpb.png)


`import qrcode`

`#linki daxil edin`
`link = "https://github.com/Rufan0"`

`qr = qrcode.QRCode(`
        `version=1,`
        `box_size=10,`
        `border=5)`
`qr.add_data(link)`

`qr.make(fit=True)`

`img = qr.make_image(fill='black', back_color='white')`
`img.save('rufan.png')`
`print("Qr Code yaradıldı ...")`
