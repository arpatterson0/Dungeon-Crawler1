# Dungeon-Crawler1
Hero fighting a villain, killing them all in order to win

Dungeon class spawn hero and villain 

THere will be an abstract being class
public abstract class Being{
    public int move; //move
    public int attack; // attack
    public int health = 100; // Heath at 100
    public int strength = 50;//attack strength
    
}
Hero and Villain classes extend being
public class Hero extends Being{
    
}
public class Villian extends Being{
    
}
Hero will be able to attack villain, vice versa. 
