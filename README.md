# file Upload and Download
> You can Upload and Download files

|Java|Maven|
|---|---|
---

|Default Home Page|
|---|
- The message next to the button indicates if you have uploaded any files.
- It also shows the amount of files you've uploaded if you've already made prior uploads.
- You can upload Movies or whatever you'd like, no matter how big the file.
> The size limit of the uploads can be easily expandable in the "application.properties" file in the back end.
> At the moment I've set the "File Size" + "Request Size" to **100000000MB**
- I've kept the User Interface as clean and simple as possible, allowing the **end user** to rather focus more on the Functionality,
 than the Graphical Interface of the program.

![Screenshot (150)](https://user-images.githubusercontent.com/81378094/123540687-91448e00-d740-11eb-987c-ae1b0b107a34.png)

---

|Uploading Features:|
|---|
- Supports Single + Multi-file uploads
- Pressing the "Choose Files" button, takes you straight to the Home directory of the User that's Logged in on
the computer at the moment.

![Screenshot (151)](https://user-images.githubusercontent.com/81378094/123541685-06ff2880-d746-11eb-9981-b8c812cdaed0.png)

---

|Uploads|
|---|
- A Progress Bar pops up if you've finished your selection.
- It's just a nice added little feature to show the **end user** the progress of their existing upload.

![Screenshot (152)](https://user-images.githubusercontent.com/81378094/123542364-8e9a6680-d749-11eb-9447-ec5f3c34a6ba.png)

---

|Processed Files
|---|
- Your uploads gets highlighted in a green tab, with a download option.
> I've used a **Blob** (Binary Large Object) to store the uploads "which could be in any multimedia or file type" as **binary data**.

![Screenshot (153)](https://user-images.githubusercontent.com/81378094/123542567-973f6c80-d74a-11eb-89a2-e4d58ace2c4e.png)

---



