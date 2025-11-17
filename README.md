# add-function-reset-draft-18
function resetMyGarage() external override {
        delete garages[msg.sender];
    }
