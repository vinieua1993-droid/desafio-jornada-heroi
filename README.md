class heroi {
    constructor(nome, poder) {
        this.nome = nome
        this.poder = poder
    }
    dizerNome() {
        console.log(` O ${this.nome} atacou usando a ${this.poder}`)
    }
}

let heroi1 = new heroi('Mago', 'Magia')
heroi1.dizerNome()
