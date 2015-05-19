# Ievads HTML

## WEB

0. Timotijs Džons "Tims" Bērnerss-Lī (angl.: *Timothy John "Tim" Berners-Lee*):
	- globālā tīmekļa izgudrotājs,
	- Vispasaules Tīmekļa konsorcija (*W3C*) pašreizējais vadītājs.
	- [wikipedia.org][1]
	- [w3.org][4]

0. Vispasaules Tīmekļa konsorcijs (angl.: *World Wide Web Consortium* jeb *W3C*) ir konsorcijs, kas veido standartus jeb "rekomendācijas" vispasaules tīmeklim ([wikipedia.org][2]).

0. Hiperteksta iezīmēšanas valoda jeb HTML (no angļu: HyperText Markup Language) ir iezīmēšanas valoda, kas ir izstrādāta tīmekļa lappušu un citas pārlūkprogrammā attēlojamas informācijas glabāšanai.
HTML specifikāciju pamatā uztur Vispasaules Tīmekļa Konsorcijs (W3C) ([wikipedia.org][3]).

### Noderīgās saites

0. [w3.org][4]
1. [html5doctor.com][5]

## Sintakse

### Iezīmes (angl. *tag*) uzbūve

- Simbols &lt;
- Taga nosaukums
- Simbols &gt;

[Piemērs][6]

### Pāra un nepāra tagi
- `<taga_nosaukums>…</taga_nosaukums>`
- `<taga_nosaukums />` vai `<taga_nosaukums>`

[Piemērs][7]

### Atribūti

- liek sākuma tagā (gan pāra, gan nepāra)
- beigu tagā NEKAD neliek
- <ins>*PAREIZI*</ins>:
	- `<taga_nosaukums atribūts="vērtība">…</taga_nosaukums>`
	- `<taga_nosaukums atribūts="vērtība" />`;
	- `<taga_nosaukums atribūts="vērtība">`;
- <del>*NEPAREIZI*</del>:
	- `<taga_nosaukums atribūts="vērtība">…</taga_nosaukums atribūts="vērtība">`

#### Flagi

Atribūts bez vērtības.

- `<taga_nosaukums atribūts>…</taga_nosaukums>`
- `<taga_nosaukums atribūts />`;
- `<taga_nosaukums atribūts>`;

[Piemērs][8]

## Elementi un to saturs

### Blokveida elementi

#### Virsraksti

- `<h1>…</h1>`
- `<h2>…</h2>`
- &hellip;
- `<h6>…</h6>`

#### Rindkopa

- `<p>… … …</p>`

#### Horizontālā svītra

- `<hr />`

#### Vienkāršs bloks

	<div>
		… … … … … …
		… … … … … …
		… … … … … …
	</div>

[Piemērs][9]
	
### Rindas (__inline__) elementi

- `<a>…</a>`
- `<strong>…</strong>`
- `<em>…</em>`
- `<span>…</span>`
- `<br />`
- &hellip;

Par `<strong>` un `em` &mdash; sk. [HTML5 Doctor][11]

[Piemērs][10]

## Speciālie simboli

Angl. __HTML entities__

Vērtīgas norādes:

- [w3schools][12]
- [w3schools][15]
- [wikipedia][13]
- [htmlarrows.com][14]

### Uzbūve

- `&`
	- nosaukums vai
	- `#` un numurs (decimālais) vai
	- `#x` un numurs (heksadecimālais)
- `;`

### Piemērs

- &cent;
- &#162;
- &#xA2;

[1]: https://lv.wikipedia.org/wiki/Tims_B%C4%93rnerss-L%C4%AB
[2]: https://lv.wikipedia.org/wiki/Vispasaules_T%C4%ABmek%C4%BCa_konsorcijs
[3]: https://lv.wikipedia.org/wiki/HTML
[4]: http://www.w3.org/Consortium/ "World Wide Web Consortium (W3C)"
[5]: http://html5doctor.com/ "HTML5 Doctor, helping you implement HTML5 today"
[6]: ./index.lv.html "Dokuments"
[7]: ./tag_containers.lv.html "Pāra un nepāra tagi"
[8]: ./attributes.lv.html "Atribūti"
[9]: ./blocks.lv.html "Blokveida elementi"
[10]: ./inline.lv.html "Inline elementi"
[11]: http://html5doctor.com/i-b-em-strong-element/ "The i, b, em, &amp; strong elements | HTML5 Doctor"
[12]: http://www.w3schools.com/html/html_entities.asp
[13]: http://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references
[14]: http://htmlarrows.com/
[15]: http://www.w3schools.com/html/html_symbols.asp