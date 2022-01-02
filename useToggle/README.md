## useToggle

### Usage  

// Call the hook which returns, current value and the toggler function

function App() {
    const [isTextChanged, setIsTextChanged] = useToggle();

    return (
        <button onClick={setIsTextChanged}>{isTextChanged ? 'Toggled' : 'Click to Toggle'}</button>
    );

}
