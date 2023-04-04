# Churn prediction
PlayNirvana Hackathon - NeoData radionica (9.1.2023. - 16.1.2023.)
Na Hackathonu smo dobili dva dataseta, sve transakcije i osobne podatke igrača na online betting platformi. Cilj je bio u nekom fiksnom danu predictati za
igrače aktivne u zadnjih 30 dana hoće li churnati (otići s platforme) u sljedećih 30 dana. Prvo smo iz inicijalnih datasetova dobili dataset sa svojstvima
za koje smo zaključili da najviše utječu na churnanje. Zatim smo taj dataset ubacili u model. Trenirali smo model na svim podacima osim zadnjih 30 dana na
kojima smo ga testirali. Koristili smo logističku regresiju s optimizacijom thresholda s raznim kombinacijama maksimiziranja recalla i specificity-a.
