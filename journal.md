# meowboard journal

## summary

| Date       | Description                      | Hours Spent |
|------------|----------------------------------|-------------|
| July 3     | Concept and layout sketching     | 2 hrs       |
| July 4     | Schematic design in KiCad        | 2.5 hrs     |
| July 5     | Schematic cleanup and footprints | 2 hrs       |
| July 6     | PCB routing                      | 2.5 hrs     |
| July 7     | DRC, polish, Gerbers             | 1.5 hrs     |
| July 8     | 3D model preview                 | 1 hr        |
| July 9     | QMK firmware + VIA config        | 2 hrs       |
| July 10    | Documentation and cleanup        | 1 hr        |

**Total Time Spent: 14.5 hours**

---

## July 3  
spent like 2 hours just vibing and thinking about what the layout should look like  
wanted something different but not too cursed  
ended up sketching a full ortholinear setup on paper  
decided to make it full-size because why not  
added keys that probably don’t need to exist  
kept thinking about adding an encoder and then added three  
by the end of it I had a rough idea and zero regrets  
looked up sukhoi logos for no reason  
saved like 8 references  
then dipped  

| Image | Description |
|-------|-------------|
|  ![image](https://github.com/user-attachments/assets/e44237c0-44e5-44f7-b99f-43783d6d8b95)  | layout sketches |

**hours spent: 2**

---

## July 4  
hit up KiCad and started making the schematic  
spent 2.5 hours mostly connecting rows and cols  
forgot like half the pins and had to redo it  
kept second guessing the diode direction  
googled “how many rows is too many” more times than I’d like to admit  
got the MCU in place and added extra footprints for future proofing  
tried making it clean but the ratsnest had other plans  
added headers for encoders and left space for RGB I’m not gonna use  
still unsure about the reset button placement  
called it a night  

| Image | Description |
|-------|-------------|
|  ![image](https://github.com/user-attachments/assets/a4ba1d47-a832-4ba4-b8dd-b18ce85a08b1) | schematic halfway done |

**hours spent: 2.5**

---

## July 5  
worked for 2 hours on cleaning up the schematic and assigning footprints  
used only MX footprints because hot swap is too much work right now  
checked trace clearances like a hundred times  
added silk for the meow logo because I had to  
mapped everything and named every net even though I didn't need to  
it looks pro now and I’m not even mad  
put the diode wave idea on the top row and yeah it slaps  
ran ERC and fixed like 15 dumb errors  
saved the file 8 times just to be safe  
finally felt like something was happening  

| Image | Description |
|-------|-------------|
|  ![image](https://github.com/user-attachments/assets/0c89c74e-b618-48f5-8106-c79502117a90)  | schematic complete with labels and logo |

**hours spent: 2**

---

## July 6  
2.5 hours of pure PCB routing  
started from the MCU and slowly routed each column  
got lost somewhere in the encoder routing chaos  
the diode wave ate half my sanity but looks amazing  
everything flows so nicely it could be a subway map  
had to delete and redo like 5 traces because I forgot the reset  
added some text on the back layer just to be cool  
it says meowboard in comic sans  
yup  
no regrets  

| Image | Description |
|-------|-------------|
|  ![image](https://github.com/user-attachments/assets/a5357aab-fefa-43c8-b3ac-402146b40037) | routed PCB with diode wave detail |

**hours spent: 2.5**

---

## July 7  
spent 1.5 hours on polishing the PCB and running DRC  
moved traces a little just to make it symmetrical  
flipped a few footprints to keep the backside clean  
checked pin mappings again because I didn’t trust myself  
measured the whole board and it's actually usable size  
exported gerbers and stared at them for a solid minute  
accidentally exported in the wrong layer set once  
got paranoid and rechecked everything  
feels super satisfying to see it come together  
can’t wait to order this now  


**hours spent: 1.5**

---

## July 8  
kinda chill today, just spent an hour working on the 3D model  
loaded everything into KiCad’s 3D viewer  
switches look so good on it even though they’re default models  
rotary encoders look chunky and I love it  
forgot to add stabilizers so now the spacebar is shaking  
added the cat logo as a cutout for no reason  
rotated it 4 times until it felt right  
considered making the board black with gold pads  
took a screenshot and used it as wallpaper  
also changed the color like 3 times just for vibes  

| Image | Description |
|-------|-------------|
|    ![image](https://github.com/user-attachments/assets/5dcfec1f-b824-4958-bd28-0b57ebd84642) | 3D viewer render  |

**hours spent: 1**

---

## July 9  
today was about the firmware so 2 hours deep in QMK  
set up the matrix with all the rows and cols  
used my old keyboard config as a base  
added encoder mapping and volume scroll  
configured layers but kept it simple for now  
got VIA working which is honestly magic  
made a custom JSON and tested it in the VIA tool  
still no underglow because I’m built like that  
made a dumb macro key that types "meow"  
uploaded it and it actually worked  


**hours spent: 2**

---

## July 10  
journaled and reflected for like an hour  
wrote all this down so I don’t forget how chaotic the process was  
cleaned up the repo and added license  
made the README look cool  
added placeholders for all the images  
shared the board with a few friends who are into keyboards  
they said it looks unhinged and I’m taking that as a win  
thinking about a rev2 already  
might add OLED  
or make it gasket mount just for drama  



**hours spent: 1**


