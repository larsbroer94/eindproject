# eindproject
tankwarz
ik ben tankwarz aan het maken dat is een spel voor 2 spellers waar bij je alle 2 een tank bent en elkaar kan kapot schieten.
een tank bestuur je met ASWD en de andere met de pijltjes. 
ze kunnen nu alleen nog maar op en neer bewegen omdat ik nog bezig ben met de rotatie.
je kan hem hier spel https://tbrrayz.github.io/eindproject/

singleton zit in het aanroepen van de game.

        public static getInstance() {
        if (! Game.instance) {
            Game.instance = new Game();
        }
        return Game.instance;
    }
    
    let g = Game.getInstance();
    

interface zit in tank1 die inplements tank.

stratery patron zit er nog niet in.

tank2 extends van gameobject.

# UML






