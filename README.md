# Mini-Project
Programming For Problem Solving 

Practical Class

MINI PROJECT 





                    Navneet Singh Parhar
RA2111038010012
Mechatronics (ROBOTICS)
Batch 2

Title- Medicine store management system
AIM- To create an Medicine store management system
Description-
This mini project is a very comprehensive one. File handling has been extensively and effectively used for almost major functions. The whole project is based on file handling as all medical records are stored in file.
Data structure have been used to store and organize records. Overall, understanding this project will provide you valuable information on how to store, edit, search and delete data using file.
Here, you can input many information like medicine Id, rack no., cabinet no., supplier’s name, unit cost, sales price, etc while adding a medicine into the store. You can also view information about report and billing. (Also check out customer billing system project.)
There are over 25 functions used in this mini project. I have divided those into the parent functions listed below to help you understand the project better.
1. Customer and supplier Id
int getcust_id();
int getsupp_id();
2. Welcome and main menu
void welcome();
void main_menu();
3. All boxes
void main_box();
void box1();
void wbox();
4. Bill slip
void bill();
5. About menu
void about();
6. Medicine menu
void medicine();
void medi_sale();
void stock();
void update_stock();
void medi_entry();
void medi_search();
void remainder();
7. Supplier menu
void supplier();
void supp_entry();
void supp_list();
void sup_update();
void search();
void search_id();
void search_name();
8. Customer menu
void customer();
void cust_search();
void search_cid();
void search_cname();
void cust_entry();
void cust_list();
void cust_update();
9. Report menu
void report_menu();
void report();
void sale_rpt();
void sale_rpt_daily();
void profit_rpt();
void pur_rpt();
void pur_rpt_daily();
void gotoxy (int x, int y) – I have been describing this function in every C mini project published on this site. You need to understand this function as it is one of the most important one used in Medical Store Management System Project.
Gotoxy function allows you to print text in any place of screen. Using this function in Code::Blocks requires coding, but it can be directly used in Turbo C. Here is a code for this function in Code::Blocks.
COORD coord = {0, 0};  // sets coordinates to (0,0) as global variables
void gotoxy (int x, int y)
{
        coord.X = x; coord.Y = y; // X and Y are the coordinates
        SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE), coord);
}
Note: In Medical Store Management System, you have to press the first character to choose the option upon running the application. For example: – (scroll down to the screenshot of main menu in output) for viewing the supplier info, enter ‘s’. Enter ‘c’ to view the customer info, enter ‘m’ for medicine and so on.
Output Screen
  

 
