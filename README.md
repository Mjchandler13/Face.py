Face.py
=======
from Graphics import *
win = Window("Shapes", 600, 600)

def face():
    #face
    face = Circle((300,300), 200)
    face.fill = Color("Beige")
    face.draw(win)

    #lips
    lips = Curve((225, 400), (275, 450), (325, 450), (375, 400))
    lips.color = Color("DarkRed")
    lips.border = 3
    lips.draw(win)

    lips = Curve((225, 400), (275, 425), (325, 425), (375, 400))
    lips.color = Color("DarkRed")
    lips.border = 3
    lips.draw(win)

    lips = Curve((225, 400), (275, 417), (325, 417), (375, 400))
    lips.color = Color("DarkRed")
    lips.border = 3
    lips.draw(win)

    #eyes
    left_eye = Oval((220,235), 40, 20)
    left_eye.fill=Color("white")
    left_eye.draw(win)
    
    left_iris = Circle((220,235), 10)
    left_iris.fill = Color("DarkBlue")
    left_iris.draw(win)
    
    left_pupil = Circle((220,235), 5)
    left_pupil.fill = Color("Black")
    left_pupil.draw(win)
    
    right_eye = Oval((380,235), 40, 20)
    right_eye.fill=Color("white")
    right_eye.draw(win)
    
    right_iris = Circle((380,235), 10)
    right_iris.fill = Color("DarkBlue")
    right_iris.draw(win)
    
    right_pupil = Circle((380,235), 5)
    right_pupil.fill = Color("Black")
    right_pupil.draw(win)
    
    #eyebrows
    right_eyebrow = Curve((340, 205), (410, 195), (430, 205), (440, 215))
    right_eyebrow.color = Color("Black")
    right_eyebrow.border = 3
    right_eyebrow.draw(win)
    
    left_eyebrow = Curve((260, 205), (190, 195), (170, 205), (160, 215))
    left_eyebrow.color = Color("Black")
    left_eyebrow.border = 3
    left_eyebrow.draw(win)

    #nose
    nose = Line((300, 340), (260, 310), (300, 280), (300, 260))
    nose.border = 3
    nose.draw(win)

    #hair
    hair = Line((145, 170), (350, 100), (350, 100), (455, 170))
    hair.border = 3
    hair.color = Color("Black")
    hair.draw(win)
    
    hair = Line((150, 170), (250, 50), (350, 50), (450, 170))
    hair.border = 3
    hair.color = Color("Black")
    hair.draw(win)
    
    hair = Line((150, 170), (250, 125), (250, 125), (450, 170))
    hair.border = 3
    hair.color = Color("Black")
    hair.draw(win)
    
    #tattoo
    big_circle = Circle((150,300), 25)
    big_circle.fill=Color("Navy")
    big_circle.draw(win)

    medium_circle = Circle((150,300), 10)
    medium_circle.fill=Color("Yellow")
    medium_circle.draw(win)
    
    small_circle = Circle((150,300), 5)
    small_circle.fill=Color("White")
    small_circle.draw(win)
face()
