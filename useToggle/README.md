## useToggle

### Usage  

function App() {  

    // Call the hook which returns, current value and the toggler function  

    const [isTextChanged, setIsTextChanged] = useToggle();
    
    return (
        <button onClick={setIsTextChanged}>{isTextChanged ? 'Toggled' : 'Click to Toggle'}</button>
    );
}