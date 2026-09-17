# Publicare pe Hostico

Arhiva `hostico-public-html.zip` conține direct fișierele care trebuie să se
afle în rădăcina publică a domeniului.

1. Deschide **cPanel → File Manager → public_html**.
2. Salvează sau elimină pagina implicită existentă, dacă există.
3. Încarcă `hostico-public-html.zip` în `public_html`.
4. Extrage arhiva în acel director.
5. Verifică să existe direct `public_html/index.html`, nu încă un director
   `public_html/public_html`.
6. Deschide domeniul prin HTTPS și verifică paginile principală și Contact.

Fișierul `.htaccess` inclus redirecționează traficul HTTP spre HTTPS, oprește
listarea directoarelor, setează antete de securitate de bază și activează
compresia și cache-ul pentru resurse statice. Certificatul SSL trebuie să fie
activ în contul Hostico înainte de publicare.

Documentație Hostico:

- https://hostico.ro/faq/unde-incarc-fisierele-site-ului-meu/
- https://hostico.ro/docs/administrarea-fisierelor-cu-file-manager-din-panoul-de-control-cpanel/
- https://hostico.ro/faq/cum-pot-sa-redirectionez-un-domeniu-din-varianta-http-spre-https/
