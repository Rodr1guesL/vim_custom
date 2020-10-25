"Este arquivo serve para configurações permanentes no VIM
"comentários são feitos numa linha iniciada com aspa dupla

"essa config adiciona números de identificação nas linhas
set number

"essa config define a auto-indentação na escrita de códigos
set autoindent

"essa config define auto-matchings de parênteses e afins
inoremap " ""<left>
inoremap ' ''<left>
inoremap ( ()<left>
inoremap < < ><left>
inoremap [ []<left>
inoremap { {}<left>
inoremap {<CR> {<CR>}<ESC>0
inoremap {;<CR> {<CR>};<ESC>0

"ativei um search pattern sem querer, agora vou ter que fixar essa config NÃO
"RETIRAR ESSA CONFIG A MENOS QUE SEJA UTILIZADO O SEARCH PATTERN
nohlsearch

"essa config faz com que o VIM já inicie no modo INSERÇÃO
startinsert
