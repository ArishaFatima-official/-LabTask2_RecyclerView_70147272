# -LabTask2_RecyclerView_70147272
# UOL Food Court Menu 🍔

An Android application developed in **Java using Android Studio** for Lab Task 02. The app displays food items in a two-column grid and allows users to view individual dish details and open the phone dialer using the **Call to Order** button.

## 📱 Project Overview

The UOL Food Court Menu provides a simple and user-friendly interface for browsing food items. Users can view food images, names, and prices, tap a food card to see more details, and access the dialer to contact a food stall.

## ✨ Features

- Displays eight food items in a two-column grid.
- Shows food images, names, and prices.
- Opens a separate details screen when a food card is tapped.
- Displays the selected dish's image, category, price, and description.
- Includes a Call to Order button that opens the phone dialer.
- Uses a yellow, white, and dark charcoal color theme.
- Uses sample stall phone numbers for testing.

## 🍕 Food Items

1. Chicken Burger
2. Chicken Pizza
3. Chicken Biryani
4. French Fries
5. Club Sandwich
6. Alfredo Pasta
7. Chicken Roll
8. Chicken Shawarma

## 🛠️ Technologies Used

- **Language:** Java
- **IDE:** Android Studio
- **UI Design:** XML Layouts
- **RecyclerView:** Displays the food menu items.
- **CardView:** Designs individual food cards.
- **GridLayoutManager:** Arranges food items in two columns.
- **Explicit Intent:** Opens the selected dish's details screen.
- **Implicit Intent (`ACTION_DIAL`):** Opens the phone dialer.
- **ArrayList:** Stores the list of food items.

## 🎨 Color Scheme

| Color | Hex Code |
|---|---|
| Yellow | `#F5C542` |
| Dark Yellow | `#D9A520` |
| Dark Charcoal | `#29251B` |
| White | `#FFFFFF` |
| Light Cream | `#FFF9E9` |

## 📂 Project Structure

```text
UOL-Food-Court-Menu/
├── app/
│   └── src/
│       └── main/
│           ├── java/com/example/uolfoodcourt/
│           │   ├── MainActivity.java
│           │   ├── Dish.java
│           │   ├── DishAdapter.java
│           │   └── DishDetailActivity.java
│           ├── res/
│           │   ├── drawable/
│           │   ├── layout/
│           │   │   ├── activity_main.xml
│           │   │   ├── item_dish.xml
│           │   │   └── activity_dish_detail.xml
│           │   └── values/
│           │       └── colors.xml
│           └── AndroidManifest.xml
└── README.md
```

## ⚙️ How to Run

1. Clone or download this repository.
2. Open Android Studio.
3. Select **Open** and choose the project folder.
4. Allow Gradle to sync and download the required dependencies.
5. Start an Android emulator or connect an Android device.
6. Click **Run** to launch the application.
7. Tap a food card to view its details.
8. Tap **Call to Order** to open the phone dialer.

## 🧪 Testing

The application can be tested by checking the following:

- The menu displays eight food items.
- The grid displays two items per row.
- Each food card opens the correct details screen.
- The selected dish's information is displayed correctly.
- The Call to Order button opens the dialer with the relevant number.
- The grid layout can be compared with a single-column `LinearLayoutManager` layout.

## 📸 Screenshots

Add screenshots of your running application to a `screenshots` folder in the repository.

Suggested screenshots:

- Main menu grid
- Chicken Burger details
- Chicken Biryani details
- Chicken Shawarma details
- Call to Order dialer screen

You can display them here after uploading the image files:

```markdown
![Main Menu](screenshots/main-menu.png)

![Chicken Burger Details](screenshots/burger-details.png)

![Chicken Biryani Details](screenshots/biryani-details.png)

![Chicken Shawarma Details](screenshots/shawarma-details.png)

![Call to Order](screenshots/call-to-order.png)
```

## 🎯 Learning Outcomes

Through this project, I practised building Android user interfaces with XML, using RecyclerView and CardView, managing data with an ArrayList, handling item click events, passing information between activities using Intents, and opening the phone dialer with `ACTION_DIAL`.

## 👩‍💻 Author

**Arisha Fatima**  
BS Software Engineering  
University of Lahore

## 📚 Academic Project

Developed as part of **Mobile Application Development — Lab Task 02**.

---

**Note:** The stall phone numbers are sample values for testing. Replace them with instructor-provided numbers if required. This project is an academic demonstration and is not connected to a live food ordering system.
