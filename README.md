# add-cur

Esse código mudarar o cursor da sua página web, só vai precisar de um navegador qualquer e um editor se texto/códigos.

# Como funciona pelo CSS

No começo do arquivo css, ou da tag `<style>` você terá que colocar o a classe ou o elemento que quer <br>
que tenha o cursor(setinha do mouse) customizada, o seguinte atributo: <br>
`cursor:url("arquivo.cur"), default` (ou o link dele se for o caso)

# Como funciona pelo JS

vai fazer o mesmo que no css só que via JavaScript, assim: <br>
`document.querySelector("body").style.cursor = "url(link), default";`

se for chamar: <br>
tag "tag",<br>
class ".nomedela", <br>
id "#nomedele", <br>


Bem simpl...

Na teoria ok, mas não tenho mais pc pra testar
