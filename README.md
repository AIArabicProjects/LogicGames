# LogicGames
this code is orginally from https://towardsdatascience.com/logicgamessolver-how-to-solve-logic-games-using-computer-vision-and-artificial-intelligence-1a4972e7e0be

إذا أردت أن تنفذ المشروع كما في أيّ مشروع في لغة بايثون هناك بعض المكتبات من المهمّ تواجدها لضمان عمل المشروع بشكل جيد:

Numpy
OpenCV
Tensorflow

قد تواجه بعض المشاكل مع التنسور فلو لذلك يفضّل تنصيب ال GPU على الاناكوندا قبل البدء بتنصيب أي مكتبة (في حال لم يتوفر لديك بشكل مسبق):


conda install tensorflow-gpu

conda install keras-gpu
من أجل لعبة السّودوكو نكتب الأمر
 python main.py sudoku 9 3
 حيث أن  sudoku  هو اسم اللعبة 9 هو حجم رقعة اللعب 3 هو عدد المربّعات في كل صفّ وعمود ضمن المنطقة الداخليّة.

من أجل لعبة ستار باتل
 python main.py stars 8 1
 حيث أنّ stars هو اسم اللعبة و 8 هو حجم الرّقعة و1 هو عدد النجوم في المنطقة الداخليّة (كما ذكرنا سابقا المستوى الأول).

من أجل لعبة سّكايسكرايبر 
python main.py skyscrapers 8 
حيث أن skyscrapers  هو اسم اللعبة و 8 هو حجم الرّقعة.

ملاحظة: إنّ حجم الرّقعة 9 يعني عدد الأسطر وعدد الأعمدة يساوي إلى 9.
