# LIUR Dokumentasi


## Deskripsi
liur adalah aplikasi dalam bentuk IaaC (Infrastructure as a Code) yang dibangun JogjaCamp atas permintaan BBT (Batam Bintan Telekomunikasi) untuk membangun infrastuktur telekomunikasi VoIP berbasis kazoo.

liur akan mem-bootstrap node / layanan yang dibutuhkan kazoo seperti:

* Kamailio
* FreeSwitch
* CouchDB
* web app (monster UI)
* Billing app (next development)
* dll

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
