Khabibullin Adel
tel. +79375297388
I am a beginner specialist in front-end development, I have been studying for a year in this specialty.
Skills: HTML, CSS, JS, TS
Code Examples: function initializePage(getUserCards, getUserProfile) {
    Promise.all([getUserCards(), getUserProfile()])
        .then(([cards, userData]) => {
            cards.forEach((cardData) => {
                placesList.append(createCard(cardData, toogleLikeCard, zoomImage, deleteModal, userData._id));
            });
            updateProfile(userData);
        })
        .catch((err) => console.error(`Ошибка: ${err}`));
}

Work Experience : I am a beginner specialist
Educationе: Yndex Practicum
English Language: A2