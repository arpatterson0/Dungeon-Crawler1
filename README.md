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
MIT License

Copyright (c) 2018 arpatterson0 mcgrey0

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
