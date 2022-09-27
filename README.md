# python_grphics
Graphycs of physics labs
The programm that helps you make graphycs for labs and other things

1) For start you have to setup:
file_name = "C://Your_dir//file_name.xls"     # it is necessary to use "xls" file

2) number_of_sheet - number of sheet in your excel file
number_of_sheet = 1

3) Setup for dots
# G_1 = Graph_excel(x_X1, x_Y1,   - start of X array
#                   x_X2, x_Y2,   - end of X array
#                   y_X1, y_Y1,   - start of Y array
#                   y_X2, y_Y2)   - end of Y array
G_1 = Graph_excel("Q", 3, "Q", 13, "R", 3, "R", 13)
G_1.fill_data(sheet.row_values) - setup the data file of your dots

4) Create arrays of you graphics
X=[G_1.X_ARR, G_2.X_ARR, G_3.X_ARR, G_4.X_ARR]
Y=[G_1.Y_ARR, G_2.Y_ARR, G_3.Y_ARR, G_4.Y_ARR]

5) Description of graphics and lines
d_arr = [
    "Зависимость \nнапряжения от фототока",
    "| $\lambda$ = 703.2нм",
    "| $\lambda$ = 659.9нм",
    "| $\lambda$ = 620.2нм",
    "| $\lambda$ = 585.8нм"]

6) Description of X and Y
xlabel="$Число \quad капель$"
ylabel="$pH$"
