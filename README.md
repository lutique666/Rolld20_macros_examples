#Simple rolld20 templates

##Weapon Attack (barbarian advantage)
###HACK FULL
&{template:atkdmg} {{mod=+1}} {{rname=GreatAxe}} {{advantage=1}} {{r1=[[d20cs>20+9-5]]}} {{r2=[[d20cs>20+9-5]]}} {{attack=1}} {{damage=1}} {{dmg1flag=1}} {{dmg1=[[1d12 + 4[STR] + 1[MAGIC]+3[RAGE]+10[FEAT]]]}} {{dmg1type=SLASHING}} {{damage=1}} {{crit1=[[2d12[CRIT]]]}} {{spelllevel=}} {{innate=}} }

###HACK
&{template:atkdmg} {{mod=+1}} {{rname=GreatAxe}} {{advantage=1}} {{r1=[[d20cs>20+9]]}} {{r2=[[d20cs>20+9]]}} {{attack=1}} {{damage=1}} {{dmg1flag=1}} {{dmg1=[[1d12 + 4[STR] + 1[MAGIC]+3[RAGE]]]}} {{dmg1type=SLASHING}} {{damage=1}} {{crit1=[[2d12[CRIT]]]}} {{spelllevel=}} {{innate=}} }

###Spirit Guardian
&{template:simple} {{rname=Spirit Guardian}} {{normal=1}} {{r1=[[2d6]]}} }} 

###Wild Surge 5
&{template:mancerroll} {{title=Wild Surge 5}} {{c1=[[1d1]]}} {{option1=[[1d6]] Force Damage}}

###Roll-result (barbarian wild surge)
&{template:mancerroll} {{title=Wild Surge}} {{c1=[[1d8]]}} {{option1=text1}} {{option2=text2}} {{option3=text3}} {{option4=text4}} {{option5=text5}} {{option6=text6}} {{option7=text7}} {{option8=text8}}
