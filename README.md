Just as the nice kids receive kind words from Santa, naughty kids receive letters of scorn.

Create a new program called naughty_letter_writer.rb that writes letters to all the naughty kids. You can refer to nice_letter_writer.rb to use as a guide.

Now take a look at templates/naughty_letter_sample.txt. This letter was composed using data from "Zoe" in kids-data.txt.

Copy templates/naughty_letter_sample.txt to naughty_letter_template.txt.erb and modify the this new .erb file to use data from the kids-data.txt data file.

Each naughty child will only receive one toy they asked for.

You should include each naughty child's infraction. You can obtain this from each line of data by using .split and splitting each line at the |.

For example, you should swap out "made a campfire in your parent's basement" with an ERB tag containing the child's infraction.

Naughty letters should be saved to the letters/naughty folder.

To sum up, the naughty letter should:

    display the child's name
    display the child's gender
    display the child's infraction
    display one random toy from their list (remember the Kaleidoscope is out of stock, so it can't be this toy)
    display the toys they're not receiving
