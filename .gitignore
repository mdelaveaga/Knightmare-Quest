controls= "type “w”, “a”, or “d” to move Forward, Left, or Right, type “stats (item)” to display the sats of that item'"
class Sword(object):
    def __init__(self, name, damage, usage):
        self.name=name
        self.damage=damage
        self.usage=usage
    def stats(self):
        print "Name: %s, Damage: %s, Durability: %s" % (self.name, self.damage, self.usage)
class Armor(object):
    def __init__(self, name, armour):
        self.name=name
        self.armour=armour
    def stats(self):
        print "Name: %s, Armor: %s" % (self.name, self.armour)
instructions="he tells you 'Your quest is to defeat Luis, the evil boss man,"
inventory={}
def start_game():
    return "Welcome to Knightmare Quest!"
def show_inventory():
    return inventory 
print start_game()
print"You arrive at a small town named Bendova, an old man approaches you,"
print instructions
print controls
name=raw_input("What is your name traveller?\n")
print "'Hello %s, it is very nice to meet you' says the old man" % name
class Monster(object):
    import random
    def __init__(self, name, health, attack1, attack2, attack1damage, attack2damage):
        self.name=name
        self.health=health
        self.attack1=attack1
        self.attack2=attack2
        self.attack1damage=attack1damage
        self.attack2damage=attack2damage
        x=random.randint(0,2)
        if x==1:
            print "The %s uses %s and it deals %s damage" % self.name, self.attack1, self.attack1damage
        elif x==2:
            print "The %s uses %s and it deals %s damage" % self.name, self.attack2, self.attack2damage
w=0
a=0
d=0
sword=Sword("Rusty sword", 5, 100)
armor=Armor("Ragged cloth armor", 20)
Health=150
while 1==1:
    answer=raw_input("What would you like to do?\n")
    if answer=="stats %s" % ("armor"):
        armor.stats()
    elif answer=="stats %s" % ("sword"):
        sword.stats()
    elif answer=="w" and w==0:
        w+=1
        print "Before you leave the town of Bendova the old man comes up to you and tells you 'it's dangerous to go alone take this' and he gives you some ragged armor and a rusty sword."
        print "You then leave the town and approach a fork in the road, in the distance you see a massive castle surrounded by ominous clouds,"
        print "the path on the right leads to the Dark Forest, and the left path leads to the Pyro Plains"
    elif answer=="a" and w==0:
        print "A very dense forest surrounds this town, you cannot go this way"
    elif answer=="d" and w==0:
        print "A very dense forest surrounds this town, you cannot go this way"
    elif answer=="d" and w==1 and d==0 and a==0:
        d+=1
        print "You decide to go to the Dark Forest"
    elif answer=="a" and w==1 and a==0 and d==0:
        import random
        a+=1
        print "You decide to go to the Pyro Plains"
        x=random.randint(1,2)
    else:
        print "Command not known"
