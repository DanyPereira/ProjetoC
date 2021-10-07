var Aluno1
var Aluno2
var Aluno3
var Aluno4
var Aluno5


var Media = parseFloat(Media)
var Nota1 = parseFloat(Nota1)
var Nota2 = parseFloat(Nota2)
var Nota3 = parseFloat(Nota3)

var Status1
var Status2
var Status3
var Status4
var Status5


Aluno1 = prompt("Digite o nome do aluno 1")
Notas = prompt("Digite as três notas do aluno, separados por vírgula")
Notas = Notas.split(",")
Nota1 = parseFloat(Notas[0])
Nota2 = parseFloat(Notas[1])
Nota3 = parseFloat(Notas[2])

Media = parseFloat(Nota1+Nota2+Nota3)/3

if (Media >=5) {
Status1 = "APROVADO"
}
else {
Status1 = "REPROVADO"
}

Aluno2 = prompt("Digite o nome do aluno 2")
Notas = prompt("Digite as três notas do aluno, separados por vírgula")
Notas = Notas.split(",")
Nota1 = parseFloat(Notas[0])
Nota2 = parseFloat(Notas[1])
Nota3 = parseFloat(Notas[2])

Media = parseFloat(Nota1+Nota2+Nota3)/3

if (Media >=5) {
Status2 = "APROVADO"
}
else {
Status2 = "REPROVADO"
}

Aluno3 = prompt("Digite o nome do aluno 3")
Notas = prompt("Digite as três notas do aluno, separados por vírgula")
Notas = Notas.split(",")
Nota1 = parseFloat(Notas[0])
Nota2 = parseFloat(Notas[1])
Nota3 = parseFloat(Notas[2])

Media = parseFloat(Nota1+Nota2+Nota3)/3

if (Media >=5) {
Status3 = "APROVADO"
}
else {
Status3 = "REPROVADO"
}


Aluno4 = prompt("Digite o nome do aluno 4")
Notas = prompt("Digite as três notas do aluno, separados por vírgula")
Notas = Notas.split(",")
Nota1 = parseFloat(Notas[0])
Nota2 = parseFloat(Notas[1])
Nota3 = parseFloat(Notas[2])

Media = parseFloat(Nota1+Nota2+Nota3)/3

if (Media >=5) {
Status4 = "APROVADO"
}
else {
Status4 = "REPROVADO"
}

Aluno5 = prompt("Digite o nome do aluno 5")
Notas = prompt("Digite as três notas do aluno, separados por vírgula")
Notas = Notas.split(",")
Nota1 = parseFloat(Notas[0])
Nota2 = parseFloat(Notas[1])
Nota3 = parseFloat(Notas[2])

Media = parseFloat(Nota1+Nota2+Nota3)/3

if (Media >=5) {
Status5 = "APROVADO"
}
else {
Status5 = "REPROVADO"
}
alert (" O aluno:  " + Aluno1  + "   está " + Status1 + " \n O aluno:  " + Aluno2  + "   está  "+ Status2 + " \n O aluno:  " + Aluno3  + "   está  "+ Status3 + " \n O aluno:  " + Aluno4  + "   está  "+ Status4 + " \n O aluno:  " + Aluno5  + "   está  "+ Status5)

