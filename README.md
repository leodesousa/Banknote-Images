# Banknote-Images

We generated an image database for USD,EUR, and BRL banknotes. The values present are: for USD  banknotes,  1,  2,  5,  10,  20,  50,  and  100;  for  EUR banknotes,  5,  10,  20,  50,  100,  200,  and  500;  for  BRL banknotes 2, 5, 10, 20, 50, and 100.

The  database  creation  was  divided  into  four  steps:i)  using  images  from  front  and  back  of  the  notes;  ii)changing  the  direction  from  horizontal  to  vertical;  iii) rotation  to  the  right  (90o);  and  iv)  rotate  to  the  left(180o). This process generates eight images for each notevalue.

As  in  day-to-day  applications,  it  is  not  common  toanalyze  the  entire  banknote.  We  included  notes  in  the test set that were divided in half and into quarters. Withthis  process,  we  increase  our  database  size,  obtaining 56 images for each class.

Another  transformation  made  in  the  images  was to  simulate  possible  events  that  could  arise  in  image acquisition:   a   median   filter   with   size   window   5×5 simulating  a  blurred  image;  applying  salt  and  pepper noise  of  5%,  and  applying  both  blurring  and  noise. Also, we increased and decreased the brightness by 30% to simulate an image acquired in a high-light and low-light environments, respectively.

To simulate images captured in different environments, where not only the banknotes is detected. We added backgrounds to banknotes, with noise, blurry, and  both.

As  a  result,  our  databases  are  composed  of  7,056 images  referring  to  USD  and  EUR,  corresponding  to 7  classes  of  values  and  6,048  images  referring  to  BRL, corresponding  to  6  classes  of  values,  each  composed  of 1,008  samples  per  note.  The images were obtained using Internet searches (USD), the work of Costa et al. (2016) (EUR) and the webpage of the Central Bank of Brazil (BRL).
