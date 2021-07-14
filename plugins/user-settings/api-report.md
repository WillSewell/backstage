## API Report File for "@backstage/plugin-user-settings"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
/// <reference types="react" />

import { ApiRef } from '@backstage/core-plugin-api';
import { BackstagePlugin } from '@backstage/core-plugin-api';
import { IconComponent } from '@backstage/core-plugin-api';
import { ProfileInfo } from '@backstage/core-plugin-api';
import { RouteRef } from '@backstage/core-plugin-api';
import { SessionApi } from '@backstage/core-plugin-api';

// @public (undocumented)
export const DefaultProviderSettings: ({
  configuredProviders,
}: Props_3) => JSX.Element;

// @public (undocumented)
export const ProviderSettingsItem: ({
  title,
  description,
  icon: Icon,
  apiRef,
}: Props_4) => JSX.Element;

// @public (undocumented)
export const Router: ({ providerSettings }: Props) => JSX.Element;

// @public (undocumented)
export const Settings: () => JSX.Element;

// @public (undocumented)
export const UserSettingsAppearanceCard: () => JSX.Element;

// @public (undocumented)
export const UserSettingsAuthProviders: ({
  providerSettings,
}: Props_2) => JSX.Element;

// @public (undocumented)
export const UserSettingsFeatureFlags: () => JSX.Element;

// @public (undocumented)
export const UserSettingsGeneral: () => JSX.Element;

// @public (undocumented)
export const UserSettingsMenu: () => JSX.Element;

// @public (undocumented)
export const UserSettingsPage: ({
  providerSettings,
}: {
  providerSettings?: JSX.Element | undefined;
}) => JSX.Element;

// @public (undocumented)
export const UserSettingsPinToggle: () => JSX.Element;

// @public (undocumented)
const userSettingsPlugin: BackstagePlugin<
  {
    settingsPage: RouteRef<undefined>;
  },
  {}
>;
export { userSettingsPlugin as plugin };
export { userSettingsPlugin };

// @public (undocumented)
export const UserSettingsProfileCard: () => JSX.Element;

// @public (undocumented)
export const UserSettingsSignInAvatar: ({ size }: Props_5) => JSX.Element;

// @public (undocumented)
export const UserSettingsThemeToggle: () => JSX.Element;

// @public (undocumented)
export const useUserProfile: () => {
  profile: ProfileInfo;
  displayName: string;
};

// (No @packageDocumentation comment for this package)
```