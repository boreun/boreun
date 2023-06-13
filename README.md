import { render } from 'react-dom';
import App from './components/app';
import { ThemeProvider } from '@material-ui/core/styles/theme';
import { createTheme } from '@material-ui/core/styles';

const theme = createTheme({
  palette: {
    type: 'dark',
  },
});

render(
  <React.StrictMode>
    <ThemeProvider theme={theme}>
      <App />
    </ThemeProvider>,
  </React.StrictMode>,
  document.getElementById('root')
);
